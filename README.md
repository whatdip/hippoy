--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.3) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==79) then v19=v0(v3(v30,1,1));return "";else local v69=v2(v0(v30,16));if v19 then local v75=v5(v69,v19);v19=nil;return v75;else return v69;end end end);local function v20(v31,v32,v33) if v33 then local v70=(v31/(2^(v32-1)))%((5 -3)^(((v33-(2 -(1 + 0))) -(v32-(1 -0))) + (2 -1))) ;return v70-(v70%(620 -(555 + 64))) ;else local v71=2^(v32-(932 -(857 + 12 + 62))) ;return (((v31%(v71 + v71))>=v71) and (569 -((1244 -(282 + 595)) + 201))) or (927 -(214 + 713)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35,v36=v1(v16,v18,v18 + (1639 -(1523 + 114)) );v18=v18 + 2 + 0 ;return (v36 * (364 -108)) + v35 ;end local function v23() local v37,v38,v39,v40=v1(v16,v18,v18 + (1068 -(68 + 997)) );v18=v18 + (1274 -(222 + 4 + 1044)) ;return (v40 * (73054774 -(12479832 + 43797726))) + (v39 * 65536) + (v38 * ((1330 -(892 + 65)) -(32 + (202 -117)))) + v37 ;end local function v24() local v41=v23();local v42=v23();local v43=1 -0 ;local v44=(v20(v42,1,(63 -27) -16 ) * (((790 -(145 + 293)) -((517 -(44 + 386)) + 263))^((1698 -(998 + 488)) -(67 + 113)))) + v41 ;local v45=v20(v42,16 + 5 ,75 -44 );local v46=((v20(v42,8 + 16 + 8 )==(3 -2)) and  -(1 -0)) or (953 -(802 + 150)) ;if (v45==0) then if (v44==(0 -0)) then return v46 * ((648 + 143) -(368 + 423)) ;else v45=1 -0 ;v43=0 + 0 ;end elseif (v45==(3044 -(915 + 82))) then return ((v44==(0 -0)) and (v46 * ((443 -(416 + 26))/0))) or (v46 * NaN) ;end return v8(v46,v45-(3266 -2243) ) * (v43 + (v44/(2^(147 -95)))) ;end local function v25(v47) local v48;if  not v47 then v47=v23();if (v47==0) then return "";end end v48=v3(v16,v18,(v18 + v47) -(773 -(201 + 571)) );v18=v18 + v47 ;local v49={};for v67=1139 -(116 + 1022) , #v48 do v49[v67]=v2(v1(v3(v48,v67,v67)));end return v6(v49);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v50=0;local v51;local v52;local v53;local v54;local v55;local v56;local v57;local v58;local v59;while true do if (v50~=(1553 -(226 + 1325))) then else v55=nil;v56=nil;v50=3;end if (v50==3) then v57=nil;v58=nil;v50=4;end if (4==v50) then v59=nil;while true do if (v51~=(0 + 0)) then else v52=0;v53=nil;v51=1;end if (v51~=(1 + 0)) then else local v93=0;while true do if (0==v93) then v54=nil;v55=nil;v93=1;end if (v93~=1) then else v51=2;break;end end end if (v51==2) then v56=nil;v57=nil;v51=2 + 1 ;end if (v51==(8 -4)) then while true do if (v52~=0) then else v53=0;v54=nil;v52=1;end if (v52~=1) then else local v98=0;local v99;while true do if (v98==(0 -0)) then v99=0 + 0 ;while true do if (1==v99) then v52=2;break;end if (v99==(1636 -(1373 + 263))) then v55=nil;v56=nil;v99=1;end end break;end end end if (v52==(1002 -(451 + 549))) then local v100=0 + 0 ;local v101;while true do if (v100~=0) then else v101=0 -0 ;while true do if (v101~=(0 -0)) then else v57=nil;v58=nil;v101=1385 -(746 + 638) ;end if (v101==(1 + 0)) then v52=4 -1 ;break;end end break;end end end if (v52==(344 -(218 + 123))) then v59=nil;while true do local v102=0;local v103;while true do if (v102~=(1581 -(1535 + 46))) then else v103=0 + 0 ;while true do if (v103~=1) then else if (v53~=0) then else local v156=0 + 0 ;local v157;while true do if (v156~=0) then else v157=0;while true do if (v157~=(560 -(306 + 254))) then else local v160=0;local v161;while true do if (v160==0) then v161=0;while true do if (v161==(0 + 0)) then v54={};v55={};v161=1;end if (v161~=1) then else v157=1;break;end end break;end end end if (v157==1) then v56={};v53=1 -0 ;break;end end break;end end end if (v53~=2) then else local v158=1467 -(899 + 568) ;local v159;while true do if (v158==0) then v159=0;while true do if (v159~=(0 + 0)) then else local v162=0 -0 ;while true do if ((603 -(268 + 335))~=v162) then else for v173=1,v58 do local v174=290 -(60 + 230) ;local v175;local v176;local v177;local v178;while true do if (v174==(573 -(426 + 146))) then v177=nil;v178=nil;v174=1 + 1 ;end if (v174~=(1456 -(282 + 1174))) then else v175=811 -(569 + 242) ;v176=nil;v174=2 -1 ;end if (v174==2) then while true do if (v175~=1) then else v178=nil;while true do if (v176==(1 + 0)) then if (v177==1) then v178=v21()~=0 ;elseif (v177==2) then v178=v24();elseif (v177==3) then v178=v25();end v59[v173]=v178;break;end if (v176~=0) then else local v188=0;while true do if ((1024 -(706 + 318))==v188) then v177=v21();v178=nil;v188=1252 -(721 + 530) ;end if ((1272 -(945 + 326))~=v188) then else v176=1;break;end end end end break;end if (v175==0) then v176=0;v177=nil;v175=1;end end break;end end end v57[7 -4 ]=v21();v162=1 + 0 ;end if (v162~=(701 -(271 + 429))) then else v159=1;break;end end end if ((1 + 0)~=v159) then else for v165=1,v23() do local v166=0;local v167;local v168;while true do if (v166==(1500 -(1408 + 92))) then v167=1086 -(461 + 625) ;v168=nil;v166=1289 -(993 + 295) ;end if (v166==(1 + 0)) then while true do if (v167~=(1171 -(418 + 753))) then else v168=v21();if (v20(v168,1 + 0 ,1 + 0 )~=0) then else local v179=0 + 0 ;local v180;local v181;local v182;local v183;local v184;while true do if (v179~=2) then else v184=nil;while true do if (v180~=(1 + 0)) then else v183=nil;v184=nil;v180=531 -(406 + 123) ;end if (v180==0) then local v189=1769 -(1749 + 20) ;while true do if (0==v189) then v181=0 + 0 ;v182=nil;v189=1;end if (1~=v189) then else v180=1323 -(1249 + 73) ;break;end end end if (v180~=2) then else while true do if (v181==0) then local v190=0 + 0 ;while true do if (1~=v190) then else v181=1146 -(466 + 679) ;break;end if (v190~=(0 -0)) then else v182=v20(v168,5 -3 ,3);v183=v20(v168,4,6);v190=1901 -(106 + 1794) ;end end end if (v181==(1 + 2)) then if (v20(v183,3,1 + 2 )==(2 -1)) then v184[4]=v59[v184[4]];end v54[v165]=v184;break;end if (v181~=(2 -1)) then else v184={v22(),v22(),nil,nil};if (v182==0) then local v195=0;local v196;while true do if (v195==(103 -(17 + 86))) then v196=0;while true do if (v196==(0 + 0)) then v184[3]=v22();v184[8 -4 ]=v22();break;end end break;end end elseif (v182==1) then v184[8 -5 ]=v23();elseif (v182==(168 -(122 + 44))) then v184[3]=v23() -(2^(27 -11)) ;elseif (v182~=3) then else local v205=0;local v206;while true do if (v205==(0 -0)) then v206=0 + 0 ;while true do if (v206~=(0 + 0)) then else v184[3]=v23() -(2^(32 -16)) ;v184[4]=v22();break;end end break;end end end v181=2;end if (v181~=2) then else local v192=65 -(30 + 35) ;while true do if (v192==1) then v181=3 + 0 ;break;end if ((1257 -(1043 + 214))==v192) then if (v20(v183,1,3 -2 )~=(1213 -(323 + 889))) then else v184[5 -3 ]=v59[v184[2]];end if (v20(v183,2,582 -(361 + 219) )~=(321 -(53 + 267))) then else v184[3]=v59[v184[1 + 2 ]];end v192=414 -(15 + 398) ;end end end end break;end end break;end if (v179~=(983 -(18 + 964))) then else v182=nil;v183=nil;v179=2;end if (v179~=(0 -0)) then else v180=0 + 0 ;v181=nil;v179=1 + 0 ;end end end break;end end break;end end end v53=853 -(20 + 830) ;break;end end break;end end end break;end if (v103==0) then local v154=0;local v155;while true do if (v154~=(0 + 0)) then else v155=126 -(116 + 10) ;while true do if (v155==0) then if (v53==3) then local v163=0 + 0 ;while true do if (v163==0) then local v170=738 -(542 + 196) ;local v171;while true do if (v170~=(0 -0)) then else v171=0;while true do if (v171==(0 + 0)) then for v185=1,v23() do v55[v185-1 ]=v28();end return v57;end end break;end end end end end if (v53~=(1 + 0)) then else local v164=0 + 0 ;while true do if (1~=v164) then else v59={};v53=4 -2 ;break;end if (v164==(0 -0)) then local v172=0;while true do if (v172~=0) then else v57={v54,v55,nil,v56};v58=v23();v172=1;end if (v172~=1) then else v164=406 -(118 + 287) ;break;end end end end end v155=3 -2 ;end if (v155~=(1122 -(118 + 1003))) then else v103=1;break;end end break;end end end end break;end end end break;end end break;end if (v51~=3) then else v58=nil;v59=nil;v51=4;end end break;end if ((0 -0)==v50) then v51=377 -(142 + 235) ;v52=nil;v50=4 -3 ;end if (1~=v50) then else v53=nil;v54=nil;v50=2;end end end local function v29(v60,v61,v62) local v63=0;local v64;local v65;local v66;while true do if (1==v63) then v66=v60[3];return function(...) local v76=v64;local v77=v65;local v78=v66;local v79=v27;local v80=1;local v81= -1;local v82={};local v83={...};local v84=v12("#",...) -1 ;local v85={};local v86={};for v90=0,v84 do if (v90>=v78) then v82[v90-v78 ]=v83[v90 + 1 ];else v86[v90]=v83[v90 + 1 ];end end local v87=(v84-v78) + 1 ;local v88;local v89;while true do v88=v76[v80];v89=v88[1];if (v89<=3) then if (v89<=1) then if (v89==0) then do return;end else local v104=0;local v105;local v106;while true do if (v104==0) then v105=v88[2];v106=v86[v88[3]];v104=1;end if (v104==1) then v86[v105 + 1 ]=v106;v86[v105]=v106[v88[4]];break;end end end elseif (v89>2) then v86[v88[2]]();else v86[v88[2]]=v88[3];end elseif (v89<=5) then if (v89==4) then v86[v88[2]]=v62[v88[3]];else local v111=0;local v112;local v113;local v114;local v115;local v116;while true do if (v111==2) then v116=v88[2];v115=v86[v88[3]];v86[v116 + 1 ]=v115;v86[v116]=v115[v88[4]];v80=v80 + 1 ;v111=3;end if (v111==5) then v88=v76[v80];v116=v88[2];v86[v116]=v86[v116](v13(v86,v116 + 1 ,v81));v80=v80 + 1 ;v88=v76[v80];v111=6;end if (0==v111) then v112=nil;v113,v114=nil;v115=nil;v116=nil;v86[v88[2]]=v62[v88[3]];v111=1;end if (v111==3) then v88=v76[v80];v86[v88[2]]=v88[3];v80=v80 + 1 ;v88=v76[v80];v116=v88[2];v111=4;end if (v111==6) then v86[v88[2]]();v80=v80 + 1 ;v88=v76[v80];do return;end break;end if (v111==1) then v80=v80 + 1 ;v88=v76[v80];v86[v88[2]]=v62[v88[3]];v80=v80 + 1 ;v88=v76[v80];v111=2;end if (4==v111) then v113,v114=v79(v86[v116](v13(v86,v116 + 1 ,v88[3])));v81=(v114 + v116) -1 ;v112=0;for v148=v116,v81 do v112=v112 + 1 ;v86[v148]=v113[v112];end v80=v80 + 1 ;v111=5;end end end elseif (v89==6) then local v117=v88[2];v86[v117]=v86[v117](v13(v86,v117 + 1 ,v81));else local v119=0;local v120;local v121;local v122;local v123;while true do if (v119==0) then v120=v88[2];v121,v122=v79(v86[v120](v13(v86,v120 + 1 ,v88[3])));v119=1;end if (v119==2) then for v151=v120,v81 do v123=v123 + 1 ;v86[v151]=v121[v123];end break;end if (v119==1) then v81=(v122 + v120) -1 ;v123=0;v119=2;end end end v80=v80 + 1 ;end end;end if (v63==0) then v64=v60[1];v65=v60[2];v63=1;end end end return v29(v28(),{},v17)(...);end return v15("LOL!043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403363O00682O7470733A2O2F6769746875622E636F6D2F776861746469702F68692O706F68756276312F626C6F622F6D61696E2F6675636B6C6500083O0012053O00013O00122O000100023O00202O00010001000300122O000300046O000100039O0000026O000100016O00017O00",v9(),...);
