<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="soqwhzc9k"/><path fill="url(#ip9dntd)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#i9m0cyc)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#iEYcEfe)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#ijlORWc)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#iaoNtlE)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#i9wiIva)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#iedLn4J)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#iufF6Id)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#iRJ8kZu)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#iald4ne)" clip-rule="evenodd" class="p2wkpjbhg"/><path fill="url(#ifenccM)" class="jodkyrb8m"/><path fill="url(#i2LlL3p)" class="jodkyrb8m"/><path fill="url(#iPqxh1A)" class="adidejbnz"/><path fill="url(#iKwzCtc)" class="adidejbnz"/><path fill="url(#i6tg68n)" class="adidejbnz"/><path fill="url(#iAqqNqc)" class="adidejbnz"/><path fill="url(#i87Pk5d)" class="adidejbnz"/><path fill="url(#iwdCfRc)" class="adidejbnz"/><path fill="url(#i28MCjt)" clip-rule="evenodd" class="fjgyzp6fc"/><path fill="url(#i03xIWd)" clip-rule="evenodd" class="a10916b_e"/><path fill="url(#i48xkdb)" clip-rule="evenodd" class="xvtv7ccem"/><path fill="url(#iaoVRrc)" clip-rule="evenodd" class="htj521bav"/><path fill="url(#iYXJIge)" class="fzrfybc1q"/><path class="bi61shneo"/><path fill="url(#ioiwN2c)" class="l4irpjpmk"/><path fill="url(#i5f4P5g)" class="l4irpjpmk"/><path fill="url(#i1ABzEc)" class="l4irpjpmk"/><path fill="url(#im4zs8g)" class="l4irpjpmk"/><path fill="url(#iWkkzde)" class="l4irpjpmk"/><path fill="url(#i1MuHjh)" class="l4irpjpmk"/><path fill="url(#iLntaCe)" class="l4irpjpmk"/><path fill="url(#iUnyqQe)" class="l4irpjpmk"/><path fill="url(#i3ut0vd)" class="l4irpjpmk"/><path fill="url(#iLwXIFb)" class="l4irpjpmk"/><path fill="url(#iW6ptEc)" class="l4irpjpmk"/><path fill="url(#iSg4rHc)" class="l4irpjpmk"/><path fill="url(#iPpR6Xb)" class="l4irpjpmk"/><path fill="url(#ihN1EPe)" class="l4irpjpmk"/><path fill="url(#iCea8xb)" class="l4irpjpmk"/><path fill="url(#iBXr7wc)" class="l4irpjpmk"/><path class="vqy_ltfen"/><path fill="url(#ixwvUyd)" class="xfw4zrbps"/><path fill="url(#ibSbhdd)" class="xfw4zrbps"/><path fill="url(#iXV9QxN)" class="xfw4zrbps"/><path fill="url(#iHnZhbd)" class="xfw4zrbps"/><path fill="url(#iCE5lCe)" class="xfw4zrbps"/><path fill="url(#iEz8j3c)" class="xfw4zrbps"/><path fill="url(#iovuA9d)" class="xfw4zrbps"/><path fill="url(#iBmzD6b)" class="xfw4zrbps"/><path fill="url(#iE32N4c)" class="ief30qbyl"/><path fill="url(#ivxlkCz)" class="ief30qbyl"/><path fill="url(#ihWfYDg)" class="ief30qbyl"/><path fill="url(#ifKjEac)" class="zuewshudh"/><path fill="url(#i6gUK0M)" class="zuewshudh"/><path fill="url(#i4MS0Eb)" class="zuewshudh"/><path fill="url(#ic7qB5c)" class="zuewshudh"/><path fill="url(#iA5KWSj)" class="zuewshudh"/><path fill="url(#ifDdOPd)" class="zuewshudh"/><path fill="url(#i6OQtKc)" clip-rule="evenodd" class="z4ry93xoo"/><path clip-rule="evenodd" class="sp0d0vb-m"/><path fill="url(#iXYe3kg)" clip-rule="evenodd" class="kbyh9_gvu"/><path fill="url(#ieqLDtd)" clip-rule="evenodd" class="kbyh9_gvu"/><path fill="url(#ipZALKe)" class="wpis97b1y"/><path clip-rule="evenodd" class="qtobwcfrb"/><path fill="url(#iaSYUsb)" clip-rule="evenodd" class="t1e-_u61d"/><path fill="url(#ilUNsSc)" clip-rule="evenodd" class="t1e-_u61d"/><path fill="url(#iNWUdgd)" class="hm372uzgc"/><path fill="url(#iYkCqDd)" class="zgdh8b08u"/><path fill="url(#iRceQKb)" class="zgdh8b08u"/><path fill="url(#iM22hmc)" class="zgdh8b08u"/><path fill="url(#iOt0PXc)" class="zgdh8b08u"/><path fill="url(#i1ySTdD)" class="zgdh8b08u"/><path fill="url(#inTqX7h)" class="zgdh8b08u"/><path fill="url(#iaEWLwc)" class="zgdh8b08u"/><path fill="url(#iEKdLwd)" class="zgdh8b08u"/><path fill="url(#iRQLfFe)" class="zgdh8b08u"/><path fill="url(#iZuv0uc)" class="zgdh8b08u"/><path fill="url(#iocGvAc)" class="zgdh8b08u"/><path fill="url(#iVN6ocd)" clip-rule="evenodd" class="ejd9yibdf"/><path fill="url(#iOKCMId)" clip-rule="evenodd" class="ejd9yibdf"/><path fill="url(#iycEtRc)" class="wq7v22g_t"/><path fill="url(#iWsGsMb)" class="wq7v22g_t"/><path fill="url(#idWpE8b)" class="wq7v22g_t"/><path fill="url(#ijeryGc)" class="wq7v22g_t"/><path fill="url(#imqW6lE)" class="wq7v22g_t"/><path fill="url(#idchLzd)" class="wq7v22g_t"/><path fill="url(#iDR24kR)" class="wq7v22g_t"/><path fill="url(#iGWgSeb)" class="wq7v22g_t"/><defs><radialGradient id="ip9dntd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 .98438 -.51448 -.42464 10.563 8.75)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="tv94cubcg"/><stop offset="1" class="ijrr8msig"/></radialGradient><radialGradient id="i9m0cyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1 .78126 -.58985 -.755 13.328 9.906)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="zekaiwv8e"/><stop offset="1" class="ijrr8msig"/></radialGradient><radialGradient id="iEYcEfe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71878 2.47459 -1.49367 -1.64106 9.094 9.25)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="aktw2vpqs"/><stop offset=".667" class="mrmug-b9v"/></radialGradient><radialGradient id="ijlORWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21874 1.78712 -1.14506 -2.06235 12.313 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="aktw2vpqs"/><stop offset=".623" class="mrmug-b9v"/></radialGradient><radialGradient id="iaoNtlE" cx="0" cy="0" r="1" gradientTransform="rotate(153.873 5.632 7.556)scale(3.65468 1.98726)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="aktw2vpqs"/><stop offset=".623" class="mrmug-b9v"/></radialGradient><radialGradient id="i9wiIva" cx="0" cy="0" r="1" gradientTransform="matrix(6.90625 6.4375 -8.27741 8.88013 11.25 12.375)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="vk96cbccl"/><stop offset=".54" class="vhy6okbtl"/></radialGradient><radialGradient id="iedLn4J" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 2.61914 -1.59052 2.3152 11.094 11.725)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="i28i0bcip"/><stop offset="1" class="bczk01kae"/></radialGradient><radialGradient id="iufF6Id" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.34375 -.49615 -.77308 16.172 11.219)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="cu8te_b2r"/><stop offset="1" class="q9ajiob4c"/></radialGradient><radialGradient id="iRJ8kZu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99999 1.54688 -.5695 -.73633 15.876 12.593)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="zz_0etkgu"/><stop offset="1" class="e45cm_b1r"/></radialGradient><radialGradient id="iald4ne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8125 1.35938 -.30474 -.40632 14.672 9.625)" gradientUnits="userSpaceOnUse"><stop offset=".151"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="ifenccM" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 4.21875 -11.28984 -1.4217 23.281 20.344)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="jdzypxk7b"/><stop offset=".632" class="xkezcve6m"/><stop offset=".905" class="uciamrb7p"/></radialGradient><radialGradient id="iPqxh1A" cx="0" cy="0" r="1" gradientTransform="matrix(-7.75003 6.7813 -3.90949 -4.46797 11.188 22.844)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="yaigewmgp"/><stop offset=".518" class="csq5216ug"/><stop offset=".766" class="flf1-pb5j"/></radialGradient><radialGradient id="iKwzCtc" cx="0" cy="0" r="1" gradientTransform="rotate(133.135 1.678 11.715)scale(4.75339 5.10812)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="wilaomb7m"/><stop offset="1" class="eyw5w3ban"/></radialGradient><radialGradient id="i87Pk5d" cx="0" cy="0" r="1" gradientTransform="rotate(135.458 -.352 13.266)scale(1.38111 .65447)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="aca1cjbfd"/><stop offset="1" class="rsrffzwqx"/></radialGradient><radialGradient id="iwdCfRc" cx="0" cy="0" r="1" gradientTransform="rotate(132.101 .801 12.684)scale(3.49581 1.27227)" gradientUnits="userSpaceOnUse"><stop class="r0dahhb7h"/><stop offset="1" class="i_zjedc-i"/></radialGradient><radialGradient id="i28MCjt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.40625 1.16939 0 7.031 27.672)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="zj-80qbav"/><stop offset=".708" class="r0lrsyiks"/><stop offset="1" class="tgyejcchd"/></radialGradient><radialGradient id="iYXJIge" cx="0" cy="0" r="1" gradientTransform="matrix(-.21875 1.34375 -2.01563 -.32812 3.281 13.531)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="bbbej-s1n"/><stop offset="1" class="idxek4bob"/></radialGradient><radialGradient id="ioiwN2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.4687 -14.2813 0 15.652 11.348)" gradientUnits="userSpaceOnUse"><stop class="tjyncjbdn"/><stop offset=".307" class="tyh44zbiq"/><stop offset=".549" class="lv38b3bho"/><stop offset="1" class="xdiz5bkvn"/></radialGradient><radialGradient id="i5f4P5g" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 7.125 -3.49223 1.68485 9.406 16.781)" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pbd6dyyci"/><stop offset="1" class="i4nn8f23f"/></radialGradient><radialGradient id="i1ABzEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.875 7.5625 -4.6134 2.97393 18.844 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="vsyieqb8q"/><stop offset=".672" class="loy93-b-o"/></radialGradient><radialGradient id="im4zs8g" cx="0" cy="0" r="1" gradientTransform="rotate(64.29 1.316 20.087)scale(2.80937 6.44154)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="u0itn-bet"/><stop offset=".824" class="bipl33gwd"/></radialGradient><radialGradient id="iWkkzde" cx="0" cy="0" r="1" gradientTransform="rotate(65.12 -.483 18.961)scale(2.37685 3.48475)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="u0itn-bet"/><stop offset=".904" class="aojleekoi"/></radialGradient><radialGradient id="i1MuHjh" cx="0" cy="0" r="1" gradientTransform="rotate(120.493 3.298 8.954)scale(3.26394 4.31592)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="wfx_lguae"/><stop offset="1" class="mx0t0998q"/></radialGradient><radialGradient id="iLntaCe" cx="0" cy="0" r="1" gradientTransform="matrix(13.25003 14.46879 -16.70167 15.29483 17.531 16.813)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="srjw_sbzu"/><stop offset=".51" class="wgdo-tbkk"/></radialGradient><radialGradient id="iUnyqQe" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 2.88183 -1.18078 .0256 9.188 15.524)" gradientUnits="userSpaceOnUse"><stop class="j0y4u-bjq"/><stop offset="1" class="bpzcqacex"/></radialGradient><radialGradient id="i3ut0vd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.96876 2.49997 -1.18101 -2.8197 3.969 9.781)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="e2-4y7b8i"/><stop offset=".861" class="qcm6zcbey"/></radialGradient><radialGradient id="iLwXIFb" cx="0" cy="0" r="1" gradientTransform="rotate(122.233 1.039 13.596)scale(1.87489 2.80703)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="b3omvkbxw"/><stop offset="1" class="lcyar85vp"/></radialGradient><radialGradient id="iW6ptEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 1.8125 -.81869 .69165 11.5 18.969)" gradientUnits="userSpaceOnUse"><stop class="ppzotxx4g"/><stop offset="1" class="e6o6albtp"/></radialGradient><radialGradient id="iSg4rHc" cx="0" cy="0" r="1" gradientTransform="rotate(149.323 8.785 11.767)scale(2.14376 1.38757)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="j-odxo--i"/><stop offset="1" class="g9fd5-c7p"/></radialGradient><radialGradient id="iPpR6Xb" cx="0" cy="0" r="1" gradientTransform="rotate(130.101 9.08 11.124)scale(1.55247 2.19637)" gradientUnits="userSpaceOnUse"><stop class="bhb65db2q"/><stop offset="1" class="aydkwwbzq"/></radialGradient><radialGradient id="ihN1EPe" cx="0" cy="0" r="1" gradientTransform="rotate(99.09 2.632 12.958)scale(1.58237 2.28653)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="u0itn-bet"/><stop offset=".782" class="y8icfotyz"/></radialGradient><radialGradient id="iCea8xb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 1.68751 -1.3406 -1.19163 22.156 14.125)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="jjtg7f5bk"/><stop offset="1" class="t-4gwgelx"/></radialGradient><radialGradient id="iBXr7wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40624 1.43751 -.6563 -.64202 23.688 12.031)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="mn5du_bdw"/><stop offset="1" class="m1vpfebwe"/></radialGradient><radialGradient id="ixwvUyd" cx="0" cy="0" r="1" gradientTransform="rotate(86.906 -4.893 12.178)scale(12.7373 6.85855)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="jk-n6_bsa"/><stop offset=".197" class="k-_xppuof"/><stop offset=".505" class="bq247gz3a"/><stop offset=".755" class="va3c2jb6o"/></radialGradient><radialGradient id="ibSbhdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46867 9.43752 -5.73795 -1.50094 5.75 16.969)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="w4d4ygbyx"/><stop offset=".704" class="dhhmpgbqg"/></radialGradient><radialGradient id="iXV9QxN" cx="0" cy="0" r="1" gradientTransform="matrix(4.15627 31.0312 -11.48207 1.53789 8.406 13.656)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="x5d2yo15t"/><stop offset=".266" class="x1a0zqblh"/><stop offset=".333" class="o2f0khw8z"/></radialGradient><radialGradient id="iHnZhbd" cx="0" cy="0" r="1" gradientTransform="matrix(.40623 3.03125 -1.11529 .14947 9.688 15.687)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="b9wcl0b9j"/><stop offset="1" class="c4xyx-0gn"/></radialGradient><radialGradient id="iCE5lCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 2.375 -1.8757 -.2468 4.438 12.219)" gradientUnits="userSpaceOnUse"><stop class="hbfwhy1mn"/><stop offset="1" class="b3qthhhbl"/></radialGradient><radialGradient id="iEz8j3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 .84375 -.64906 -.08414 4.406 13.047)" gradientUnits="userSpaceOnUse"><stop class="t8y_ghwyw"/><stop offset="1" class="i_w124bxs"/></radialGradient><radialGradient id="iovuA9d" cx="0" cy="0" r="1" gradientTransform="matrix(-17.31234 14.71886 -9.02508 -10.61531 7.438 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="u4vr6me0r"/><stop offset=".333" class="nkfbk81xs"/></radialGradient><radialGradient id="iBmzD6b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -3.64 9.984)scale(.6875)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="fyqn6wbeu"/><stop offset="1" class="qh_ie6b-d"/></radialGradient><radialGradient id="iE32N4c" cx="0" cy="0" r="1" gradientTransform="matrix(4.13435 1.93949 -.7171 1.5286 4.106 11.313)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="kwz7bpxjg"/><stop offset="1" class="d1oiwtb2m"/></radialGradient><radialGradient id="ivxlkCz" cx="0" cy="0" r="1" gradientTransform="rotate(102.059 -3.415 7.034)scale(7.03014 7.95678)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="spa5e3fcg"/><stop offset=".274" class="vstancbmp"/></radialGradient><radialGradient id="ihWfYDg" cx="0" cy="0" r="1" gradientTransform="rotate(68.11 -8.206 9.484)scale(4.95067 5.55539)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y_n4-hb7l"/><stop offset=".6" class="p9p-pabzf"/></radialGradient><radialGradient id="ifKjEac" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.875 -15.5175 0 12.678 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="p9k97eoks"/><stop offset=".229" class="tp85s9b4z"/><stop offset=".26" class="dh4v6fbuk"/></radialGradient><radialGradient id="i6gUK0M" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71873 3.40627 -3.1167 -3.4026 13.813 19.531)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="s8vy46qrr"/><stop offset="1" class="fp835u7xr"/></radialGradient><radialGradient id="i4MS0Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4375 4 -2.57576 -2.21355 9.938 18.281)" gradientUnits="userSpaceOnUse"><stop offset=".338" class="m023mgbmi"/><stop offset="1" class="v544b-bjz"/></radialGradient><radialGradient id="ic7qB5c" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 3.31 13.181)scale(3.8309 1.71522)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="t6f0-m1fg"/><stop offset="1" class="el81gqbhz"/></radialGradient><radialGradient id="iA5KWSj" cx="0" cy="0" r="1" gradientTransform="rotate(133.608 .052 13.69)scale(11.8254 6.8394)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="hwk5_4boq"/><stop offset=".43" class="e04declrf"/></radialGradient><radialGradient id="ifDdOPd" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 .50586 -.1348 .65374 10.422 18.469)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="ppzotxx4g"/><stop offset="1" class="e6o6albtp"/></radialGradient><radialGradient id="i6OQtKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.39648 -1.56505 0 10.125 25.854)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="d8oz9ob2i"/><stop offset=".536" class="xxe7bw5id"/><stop offset="1" class="fmfc_wbuo"/></radialGradient><radialGradient id="iXYe3kg" cx="0" cy="0" r="1" gradientTransform="rotate(12.339 -12.918 120.87)scale(1.21558)" gradientUnits="userSpaceOnUse"><stop class="e1pey-b_t"/><stop offset="1" class="ckf5sdazc"/></radialGradient><radialGradient id="ieqLDtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55077 1.56251 -.69573 -.6905 27.113 3.813)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="g4w7hrbkt"/><stop offset="1" class="tyiamcdxv"/></radialGradient><radialGradient id="ipZALKe" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 2.6875 -2.18734 .1526 7.344 17.438)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="jpbuv4z6p"/><stop offset=".538" class="sgf1uqdnv"/><stop offset=".861" class="znevj04kj"/></radialGradient><radialGradient id="iaSYUsb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.07812 -3.96875 .59636 -.76306 29.297 20.874)" gradientUnits="userSpaceOnUse"><stop offset=".037" class="b876zokjp"/><stop offset="1" class="z53hbcbjw"/></radialGradient><radialGradient id="iNWUdgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 .51563 -.45655 -.33203 6.688 13.281)" gradientUnits="userSpaceOnUse"><stop class="k3ytyig3r"/><stop offset=".877" class="wuk_avbmq"/></radialGradient><radialGradient id="iYkCqDd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49997 5.28127 -4.54116 -3.0095 26.469 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="u1mwyksmb"/><stop offset="1" class="xx8-k_svk"/></radialGradient><radialGradient id="iM22hmc" cx="0" cy="0" r="1" gradientTransform="matrix(7.21873 -8.78123 6.48106 5.32785 24.906 12.063)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aj7x89b1w"/><stop offset=".52" class="n34hwfbmr"/></radialGradient><radialGradient id="iOt0PXc" cx="0" cy="0" r="1" gradientTransform="rotate(55.505 -3.113 30.113)scale(6.78708)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="adaqr7bhh"/><stop offset=".518" class="xbbmtxopf"/></radialGradient><radialGradient id="i1ySTdD" cx="0" cy="0" r="1" gradientTransform="rotate(120.906 9.666 14.233)scale(5.35397 1.69887)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="dh5aj8b0d"/><stop offset="1" class="w1tgf338g"/></radialGradient><radialGradient id="inTqX7h" cx="0" cy="0" r="1" gradientTransform="matrix(2.90625 .21875 -.38891 5.16696 24.938 13.563)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="ullfjub9h"/><stop offset=".72" class="mlbco312m"/></radialGradient><radialGradient id="iaEWLwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.3252 -5.31204 0 27.25 11.625)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="ullfjub9h"/><stop offset=".72" class="mlbco312m"/></radialGradient><radialGradient id="iEKdLwd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 1.25 -5.01524 6.26906 26.813 13.719)" gradientUnits="userSpaceOnUse"><stop class="wl1g7-bgs"/><stop offset=".595" class="j2h8g060w"/></radialGradient><radialGradient id="iRQLfFe" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.3125 -1.94289 1.20274 28 12.938)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="zt5bgcbxe"/><stop offset="1" class="b7r27eb5g"/></radialGradient><radialGradient id="iocGvAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68751 1.34374 -.39685 -.20304 23.594 11.156)" gradientUnits="userSpaceOnUse"><stop class="ffm7lo8_s"/><stop offset="1" class="k25j0g9gl"/></radialGradient><radialGradient id="iVN6ocd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4375 .03127 -.01163 -.9067 30 11.063)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="rygoagjtr"/><stop offset=".516" class="md015wkid"/><stop offset="1" class="y7r8hibxu"/></radialGradient><radialGradient id="iOKCMId" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 .2793 -.12831 1.0337 28 10.063)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="g8wmbcb2k"/><stop offset="1" class="qhetk2b9v"/></radialGradient><radialGradient id="iycEtRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21583 1.04687 -1.01846 -.20997 22.594 8.578)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="tif0eko9x"/><stop offset=".499" class="wdfb-pb5p"/><stop offset="1" class="y7790bcck"/></radialGradient><radialGradient id="idchLzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71973 .36818 -.1581 -.30907 23.099 8.313)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="i8ztekb7k"/><stop offset="1" class="vhsp-dbci"/></radialGradient><radialGradient id="iDR24kR" cx="0" cy="0" r="1" gradientTransform="matrix(0 .13672 -.30382 0 23.047 8.477)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="qctwb6bnz"/><stop offset="1" class="cw-p1ebgd"/></radialGradient><radialGradient id="iGWgSeb" cx="0" cy="0" r="1" gradientTransform="rotate(134.999 9.545 8.974)scale(.41985 .40845)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="ylvonurqj"/><stop offset="1" class="xzxiu9vrp"/></radialGradient><linearGradient id="i2LlL3p" x1="26.781" x2="26.25" y1="17.813" y2="18.438" gradientUnits="userSpaceOnUse"><stop offset=".338" class="esd3q5bgp"/><stop offset="1" class="ubqo6hdan"/></linearGradient><linearGradient id="i6tg68n" x1="7.344" x2="7.75" y1="20.469" y2="20.875" gradientUnits="userSpaceOnUse"><stop class="afsow9bqm"/><stop offset="1" class="ho3y3mbwc"/></linearGradient><linearGradient id="iAqqNqc" x1="5.943" x2="6.469" y1="23.438" y2="23.438" gradientUnits="userSpaceOnUse"><stop class="afsow9bqm"/><stop offset="1" class="jt-9y2bvn"/></linearGradient><linearGradient id="i03xIWd" x1="23.828" x2="24.625" y1="10.016" y2="10.844" gradientUnits="userSpaceOnUse"><stop offset=".052" class="m6m3b-0tm"/><stop offset=".223" class="jyiw6mm_k"/><stop offset=".406" class="gthme523z"/><stop offset=".807" class="x8b-e-d1e"/></linearGradient><linearGradient id="i48xkdb" x1="23.914" x2="23.914" y1="8.469" y2="9.403" gradientUnits="userSpaceOnUse"><stop class="s95j2xufq"/><stop offset=".145" class="ztzwxpnbl"/><stop offset=".567" class="lwswm-b-p"/><stop offset=".769" class="mb-awm9ue"/><stop offset="1" class="o4hbq1c-a"/></linearGradient><linearGradient id="iaoVRrc" x1="23.563" x2="24.281" y1="6.5" y2="7.234" gradientUnits="userSpaceOnUse"><stop class="pb175rb4h"/><stop offset=".225" class="ui8rsxbiv"/><stop offset=".391" class="vk-1kikqd"/><stop offset=".621" class="y3bk2ibki"/><stop offset="1" class="uupturd4r"/></linearGradient><linearGradient id="ilUNsSc" x1="28.781" x2="28.438" y1="19.813" y2="20.25" gradientUnits="userSpaceOnUse"><stop class="c_lo7yb-h"/><stop offset="1" class="h2u_8cbhk"/></linearGradient><linearGradient id="iRceQKb" x1="22.313" x2="23.563" y1="11.875" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="wgdo-tbkk"/><stop offset="1" class="pf-b2yb7o"/></linearGradient><linearGradient id="iZuv0uc" x1="25.168" x2="25.168" y1="9.563" y2="11.219" gradientUnits="userSpaceOnUse"><stop offset="0" class="sh2a1786y"/><stop offset="1" class="lzymcv4va"/></linearGradient><linearGradient id="iWsGsMb" x1="22.664" x2="22.625" y1="8.063" y2="8.594" gradientUnits="userSpaceOnUse"><stop offset=".013" class="y3bk2ibki"/><stop offset="1" class="oa9p7qvci"/></linearGradient><linearGradient id="idWpE8b" x1="23.121" x2="22.5" y1="8.84" y2="8.555" gradientUnits="userSpaceOnUse"><stop offset=".263" class="dy_daob_l"/><stop offset="1" class="oa9p7qvci"/></linearGradient><linearGradient id="ijeryGc" x1="22.378" x2="22.378" y1="9.586" y2="9.016" gradientUnits="userSpaceOnUse"><stop offset=".395" class="gvgp-u1cz"/><stop offset="1" class="f650tcbeh"/></linearGradient><linearGradient id="imqW6lE" x1="21.719" x2="22.273" y1="8.063" y2="8.523" gradientUnits="userSpaceOnUse"><stop offset=".35" class="p_niyfbkp"/><stop offset=".789" class="m2c5-5sfx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:donkey" /></template>
<style>
.a10916b_e {
  fill-rule: evenodd;
  d: path("M26.01 4.733a.48.48 0 0 1 0 .68l-3.028 3.028h2.106c.643 0 .965.777.51 1.232l-2.03 2.031a.481.481 0 1 1-.681-.68l1.62-1.621h-2.106a.722.722 0 0 1-.51-1.232l3.438-3.438a.48.48 0 0 1 .68 0");
}

.aca1cjbfd {
  stop-color: var(--svg-color--a3869e, #A3869E);
}

.adaqr7bhh {
  stop-color: var(--svg-color--988b82, #988B82);
  stop-opacity: 0;
}

.adidejbnz {
  d: path("m5.95 26.01l-.006-3.664c0-.255.1-.499.28-.68l4.53-4.564l2.887 1.924l-5.401 4.206a.96.96 0 0 0-.371.762l.004 2.013a.48.48 0 0 1-.48.483H6.43a.48.48 0 0 1-.48-.48");
}

.afsow9bqm {
  stop-color: var(--svg-color--605551, #605551);
}

.aj7x89b1w {
  stop-color: var(--svg-color--d5aec7, #D5AEC7);
  stop-opacity: 0;
}

.aktw2vpqs {
  stop-color: var(--svg-color--464548, #464548);
}

.aojleekoi {
  stop-color: var(--svg-color--ad9f95, #AD9F95);
  stop-opacity: 0;
}

.aydkwwbzq {
  stop-color: var(--svg-color--c3b2a8, #C3B2A8);
  stop-opacity: 0;
}

.b3omvkbxw {
  stop-color: var(--svg-color--d8b2c8, #D8B2C8);
}

.b3qthhhbl {
  stop-color: var(--svg-color--b29e9d, #B29E9D);
  stop-opacity: 0;
}

.b7r27eb5g {
  stop-color: var(--svg-color--d9b3ca, #D9B3CA);
  stop-opacity: 0;
}

.b876zokjp {
  stop-color: var(--svg-color--8f8683, #8F8683);
}

.b9wcl0b9j {
  stop-color: var(--svg-color--be9daa, #BE9DAA);
}

.bbbej-s1n {
  stop-color: var(--svg-color--9c8391, #9C8391);
}

.bczk01kae {
  stop-color: var(--svg-color--3c383d, #3C383D);
  stop-opacity: 0;
}

.bhb65db2q {
  stop-color: var(--svg-color--cdbdb1, #CDBDB1);
}

.bi61shneo {
  fill: var(--svg-color--d8c0c1, #D8C0C1);
  d: path("M8.831 15.53v1.596c-.526.358-1.706 1.154-1.706 1.154s-1.072-.721-1.735-1.154l-1.13-3.874l-2.015-1.791a.19.19 0 0 1-.008-.275a1.416 1.416 0 0 1 1.786-.177l.478.319a5.463 5.463 0 0 1 7.945-.234l.234.234l1.61 1.432a2.165 2.165 0 0 0 2.408.319l4.466-2.236a2.643 2.643 0 0 1 3.813 2.624l-.1 1.01a3.9 3.9 0 0 1-1.482 2.688L19.06 20.54a4.81 4.81 0 0 1-6.652-.717z");
}

.bipl33gwd {
  stop-color: var(--svg-color--9f9188, #9F9188);
  stop-opacity: 0;
}

.bpzcqacex {
  stop-color: var(--svg-color--ba98a7, #BA98A7);
  stop-opacity: 0;
}

.bq247gz3a {
  stop-color: var(--svg-color--b7a2a2, #B7A2A2);
}

.c_lo7yb-h {
  stop-color: var(--svg-color--6f6761, #6F6761);
}

.c4xyx-0gn {
  stop-color: var(--svg-color--be9daa, #BE9DAA);
  stop-opacity: 0;
}

.ckf5sdazc {
  stop-color: var(--svg-color--3b3040, #3B3040);
  stop-opacity: 0;
}

.csq5216ug {
  stop-color: var(--svg-color--a38d96, #A38D96);
}

.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.cw-p1ebgd {
  stop-color: var(--svg-color--bcaaa2, #BCAAA2);
  stop-opacity: 0;
}

.d1oiwtb2m {
  stop-color: var(--svg-color--c09fb2, #C09FB2);
}

.d8oz9ob2i {
  stop-color: var(--svg-color--a18f96, #A18F96);
}

.dh4v6fbuk {
  stop-color: var(--svg-color--ac949a, #AC949A);
}

.dh5aj8b0d {
  stop-color: var(--svg-color--c1a8ad, #C1A8AD);
}

.dhhmpgbqg {
  stop-color: var(--svg-color--c6b3ad, #C6B3AD);
}

.dy_daob_l {
  stop-color: var(--svg-color--cab5b2, #CAB5B2);
}

.e04declrf {
  stop-color: var(--svg-color--d8b5c8, #D8B5C8);
}

.e1pey-b_t {
  stop-color: var(--svg-color--3b3040, #3B3040);
}

.e2-4y7b8i {
  stop-color: var(--svg-color--a0928b, #A0928B);
}

.e45cm_b1r {
  stop-color: var(--svg-color--1d1a18, #1D1A18);
  stop-opacity: 0;
}

.e6o6albtp {
  stop-color: var(--svg-color--ae949c, #AE949C);
  stop-opacity: 0;
}

.ejd9yibdf {
  fill-rule: evenodd;
  d: path("M28.557 12.266v-1.924h.962a.48.48 0 0 1 .48.48v.963a.48.48 0 0 1-.48.481z");
}

.el81gqbhz {
  stop-color: var(--svg-color--d9b4cd, #D9B4CD);
  stop-opacity: 0;
}

.esd3q5bgp {
  stop-color: var(--svg-color--998f85, #998F85);
}

.eyw5w3ban {
  stop-color: var(--svg-color--8c7b7c, #8C7B7C);
  stop-opacity: 0;
}

.f650tcbeh {
  stop-color: var(--svg-color--baa2a5, #BAA2A5);
  stop-opacity: 0;
}

.ffm7lo8_s {
  stop-color: var(--svg-color--8e8179, #8E8179);
}

.fjgyzp6fc {
  fill-rule: evenodd;
  d: path("m5.949 25.854l.001.962c0 .266.216.48.481.48h.962a.48.48 0 0 0 .481-.481l-.001-.962z");
}

.flf1-pb5j {
  stop-color: var(--svg-color--746964, #746964);
}

.fmfc_wbuo {
  stop-color: var(--svg-color--66595d, #66595D);
}

.fp835u7xr {
  stop-color: var(--svg-color--dbbfc6, #DBBFC6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyqn6wbeu {
  stop-color: var(--svg-color--a89098, #A89098);
}

.fzrfybc1q {
  d: path("m2.163 13.275l2.82.94V12.77l-1.586-.528a.99.99 0 0 0-1.301.938a.1.1 0 0 0 .067.094");
}

.g4w7hrbkt {
  stop-color: var(--svg-color--5a5a5a, #5A5A5A);
}

.g8wmbcb2k {
  stop-color: var(--svg-color--6f6760, #6F6760);
}

.g9fd5-c7p {
  stop-color: var(--svg-color--cca7bf, #CCA7BF);
  stop-opacity: 0;
}

.gthme523z {
  stop-color: var(--svg-color--c2aea8, #C2AEA8);
}

.gvgp-u1cz {
  stop-color: var(--svg-color--a38c91, #A38C91);
}

.h2u_8cbhk {
  stop-color: var(--svg-color--7c746e, #7C746E);
  stop-opacity: 0;
}

.hbfwhy1mn {
  stop-color: var(--svg-color--b29e9d, #B29E9D);
}

.hm372uzgc {
  d: path("M6.5 13.95a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.ho3y3mbwc {
  stop-color: var(--svg-color--766966, #766966);
  stop-opacity: 0;
}

.htj521bav {
  fill-rule: evenodd;
  d: path("M26.01 4.733a.48.48 0 0 1 0 .68l-3.028 3.028l-.904.888a.724.724 0 0 1-.187-1.158l3.438-3.438a.48.48 0 0 1 .68 0");
}

.hwk5_4boq {
  stop-color: var(--svg-color--d8b5c8, #D8B5C8);
  stop-opacity: 0;
}

.i_w124bxs {
  stop-color: var(--svg-color--b49ea0, #B49EA0);
  stop-opacity: 0;
}

.i_zjedc-i {
  stop-color: var(--svg-color--786569, #786569);
  stop-opacity: 0;
}

.i28i0bcip {
  stop-color: var(--svg-color--3c383d, #3C383D);
}

.i4nn8f23f {
  stop-color: var(--svg-color--cdaeba, #CDAEBA);
  stop-opacity: 0;
}

.i8ztekb7k {
  stop-color: var(--svg-color--bfa8aa, #BFA8AA);
}

.idxek4bob {
  stop-color: var(--svg-color--6f665f, #6F665F);
}

.ief30qbyl {
  d: path("m4.26 13.252l-2.015-1.791a.19.19 0 0 1-.008-.275a1.416 1.416 0 0 1 1.786-.177l.774.452c.234.148.43.57.273 1.062c-.146.46-.43.649-.81.73");
}

.ijrr8msig {
  stop-color: var(--svg-color--515151, #515151);
  stop-opacity: 0;
}

.j-odxo--i {
  stop-color: var(--svg-color--cca7bf, #CCA7BF);
}

.j0y4u-bjq {
  stop-color: var(--svg-color--ba98a7, #BA98A7);
}

.j2h8g060w {
  stop-color: var(--svg-color--dabec4, #DABEC4);
  stop-opacity: 0;
}

.jdzypxk7b {
  stop-color: var(--svg-color--b291a9, #B291A9);
}

.jjtg7f5bk {
  stop-color: var(--svg-color--9f908c, #9F908C);
}

.jk-n6_bsa {
  stop-color: var(--svg-color--e3c4ce, #E3C4CE);
}

.jodkyrb8m {
  d: path("m24.227 19.6l-5.774.962l2.887-3.85h3.483c.236 0 .463.087.64.244l2.812 2.5l.113.74a.48.48 0 0 1-.13.407l-.457.471a.48.48 0 0 1-.412.142l-.741-.103z");
}

.jpbuv4z6p {
  stop-color: var(--svg-color--ffe5fe, #FFE5FE);
}

.jt-9y2bvn {
  stop-color: var(--svg-color--7e6e71, #7E6E71);
  stop-opacity: 0;
}

.jyiw6mm_k {
  stop-color: var(--svg-color--bdaba5, #BDABA5);
}

.k-_xppuof {
  stop-color: var(--svg-color--d2b4bf, #D2B4BF);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k25j0g9gl {
  stop-color: var(--svg-color--8e8179, #8E8179);
  stop-opacity: 0;
}

.k3ytyig3r {
  stop-color: var(--svg-color--504f50, #504F50);
}

.kbyh9_gvu {
  fill-rule: evenodd;
  d: path("M26.152 5.553c.531 0 .962-.43.962-.962V3.87a.24.24 0 0 0-.24-.24h-.722a.962.962 0 0 0 0 1.924");
}

.kwz7bpxjg {
  stop-color: var(--svg-color--d5c0bb, #D5C0BB);
}

.l4irpjpmk {
  d: path("M8.831 15.53v1.596c-.526.358-1.706 1.154-1.706 1.154s-1.072-.721-1.735-1.154l-1.13-3.874l-2.015-1.791a.19.19 0 0 1-.008-.275a1.416 1.416 0 0 1 1.786-.177l.478.319a5.463 5.463 0 0 1 7.945-.234l.234.234l1.61 1.432a2.165 2.165 0 0 0 2.408.319l4.466-2.236a2.643 2.643 0 0 1 3.813 2.624l-.1 1.01a3.9 3.9 0 0 1-1.482 2.688L19.06 20.54a4.81 4.81 0 0 1-6.652-.717z");
}

.lcyar85vp {
  stop-color: var(--svg-color--d8b2c8, #D8B2C8);
  stop-opacity: 0;
}

.loy93-b-o {
  stop-color: var(--svg-color--c1aea8, #C1AEA8);
  stop-opacity: 0;
}

.lv38b3bho {
  stop-color: var(--svg-color--dcc1c7, #DCC1C7);
}

.lwswm-b-p {
  stop-color: var(--svg-color--c8b2b1, #C8B2B1);
}

.lzymcv4va {
  stop-color: var(--svg-color--bcaca3, #BCACA3);
  stop-opacity: 0;
}

.m023mgbmi {
  stop-color: var(--svg-color--a3928d, #A3928D);
}

.m1vpfebwe {
  stop-color: var(--svg-color--93857e, #93857E);
  stop-opacity: 0;
}

.m2c5-5sfx {
  stop-color: var(--svg-color--b9a5a3, #B9A5A3);
  stop-opacity: 0;
}

.m6m3b-0tm {
  stop-color: var(--svg-color--8d8079, #8D8079);
}

.mb-awm9ue {
  stop-color: var(--svg-color--bfa7a9, #BFA7A9);
}

.md015wkid {
  stop-color: var(--svg-color--95828b, #95828B);
}

.mlbco312m {
  stop-color: var(--svg-color--e0c4ca, #E0C4CA);
  stop-opacity: 0;
}

.mn5du_bdw {
  stop-color: var(--svg-color--93857e, #93857E);
}

.mrmug-b9v {
  stop-color: var(--svg-color--3f3b42, #3F3B42);
  stop-opacity: 0;
}

.mx0t0998q {
  stop-color: var(--svg-color--cfbeb4, #CFBEB4);
  stop-opacity: 0;
}

.n34hwfbmr {
  stop-color: var(--svg-color--cfabbf, #CFABBF);
}

.nkfbk81xs {
  stop-color: var(--svg-color--82776f, #82776F);
}

.o2f0khw8z {
  stop-color: var(--svg-color--917e81, #917E81);
}

.o4hbq1c-a {
  stop-color: var(--svg-color--9f888e, #9F888E);
}

.oa9p7qvci {
  stop-color: var(--svg-color--ceb7b8, #CEB7B8);
  stop-opacity: 0;
}

.p_niyfbkp {
  stop-color: var(--svg-color--94867f, #94867F);
}

.p2wkpjbhg {
  fill-rule: evenodd;
  d: path("m8.43 7.876l-3.45 3.45l1.925 1.925l.962-.962l1.925 1.924l1.924 1.925l4.471-4.471a.48.48 0 0 0 0-.68l-.223-.224a1.924 1.924 0 0 0-2.722 0l1.02-1.02a.48.48 0 0 0 0-.681l-.223-.224a1.924 1.924 0 0 0-2.721 0l.058-.058a.48.48 0 0 0 0-.68l-.224-.224a1.924 1.924 0 0 0-2.721 0");
}

.p9k97eoks {
  stop-color: var(--svg-color--eed1d6, #EED1D6);
}

.p9p-pabzf {
  stop-color: var(--svg-color--90837d, #90837D);
}

.pb175rb4h {
  stop-color: var(--svg-color--8c7f78, #8C7F78);
}

.pbd6dyyci {
  stop-color: var(--svg-color--bc9caa, #BC9CAA);
}

.pf-b2yb7o {
  stop-color: var(--svg-color--c5b2ac, #C5B2AC);
  stop-opacity: 0;
}

.ppzotxx4g {
  stop-color: var(--svg-color--8d7b79, #8D7B79);
}

.q9ajiob4c {
  stop-color: var(--svg-color--49474a, #49474A);
  stop-opacity: 0;
}

.qcm6zcbey {
  stop-color: var(--svg-color--b4a39d, #B4A39D);
  stop-opacity: 0;
}

.qctwb6bnz {
  stop-color: var(--svg-color--b0a094, #B0A094);
}

.qh_ie6b-d {
  stop-color: var(--svg-color--a89098, #A89098);
  stop-opacity: 0;
}

.qhetk2b9v {
  stop-color: var(--svg-color--6f6760, #6F6760);
  stop-opacity: 0;
}

.qtobwcfrb {
  fill: var(--svg-color--836a81, #836A81);
  fill-rule: evenodd;
  d: path("m28.244 19.43l.892.793a.48.48 0 0 1 .02.7l-.811.811a.48.48 0 0 1-.595.068l-1.156-.722z");
}

.r0dahhb7h {
  stop-color: var(--svg-color--786569, #786569);
}

.r0lrsyiks {
  stop-color: var(--svg-color--6c5d65, #6C5D65);
}

.rsrffzwqx {
  stop-color: var(--svg-color--a3869e, #A3869E);
  stop-opacity: 0;
}

.rygoagjtr {
  stop-color: var(--svg-color--9c918d, #9C918D);
}

.s8vy46qrr {
  stop-color: var(--svg-color--e7c5d4, #E7C5D4);
}

.s95j2xufq {
  stop-color: var(--svg-color--afa094, #AFA094);
}

.sgf1uqdnv {
  stop-color: var(--svg-color--e1c5e2, #E1C5E2);
}

.sh2a1786y {
  stop-color: var(--svg-color--ac9e93, #AC9E93);
}

.soqwhzc9k {
  fill: var(--svg-color--1f1c1a, #1F1C1A);
  fill-rule: evenodd;
  d: path("m8.43 7.876l-3.45 3.45l1.925 1.925l.962-.962l1.925 1.924l1.924 1.925l4.471-4.471a.48.48 0 0 0 0-.68l-.223-.224a1.924 1.924 0 0 0-2.722 0l1.02-1.02a.48.48 0 0 0 0-.681l-.223-.224a1.924 1.924 0 0 0-2.721 0l.058-.058a.48.48 0 0 0 0-.68l-.224-.224a1.924 1.924 0 0 0-2.721 0");
}

.sp0d0vb-m {
  fill: var(--svg-color--202020, #202020);
  fill-rule: evenodd;
  d: path("M26.152 5.553c.531 0 .962-.43.962-.962V3.87a.24.24 0 0 0-.24-.24h-.722a.962.962 0 0 0 0 1.924");
}

.spa5e3fcg {
  stop-color: var(--svg-color--b59fa2, #B59FA2);
  stop-opacity: 0;
}

.srjw_sbzu {
  stop-color: var(--svg-color--d0bcb8, #D0BCB8);
  stop-opacity: 0;
}

.t-4gwgelx {
  stop-color: var(--svg-color--9f908c, #9F908C);
  stop-opacity: 0;
}

.t1e-_u61d {
  fill-rule: evenodd;
  d: path("m28.244 19.43l.892.793a.48.48 0 0 1 .02.7l-.811.811a.48.48 0 0 1-.595.068l-1.156-.722z");
}

.t6f0-m1fg {
  stop-color: var(--svg-color--d9b4cd, #D9B4CD);
}

.t8y_ghwyw {
  stop-color: var(--svg-color--b49ea0, #B49EA0);
}

.tgyejcchd {
  stop-color: var(--svg-color--5c5054, #5C5054);
}

.tif0eko9x {
  stop-color: var(--svg-color--dcc7c2, #DCC7C2);
}

.tjyncjbdn {
  stop-color: var(--svg-color--968a7f, #968A7F);
}

.tp85s9b4z {
  stop-color: var(--svg-color--c6aab3, #C6AAB3);
}

.tv94cubcg {
  stop-color: var(--svg-color--515151, #515151);
}

.tyh44zbiq {
  stop-color: var(--svg-color--cab8b0, #CAB8B0);
}

.tyiamcdxv {
  stop-color: var(--svg-color--4f4f50, #4F4F50);
  stop-opacity: 0;
}

.u0itn-bet {
  stop-color: var(--svg-color--8c8177, #8C8177);
}

.u1mwyksmb {
  stop-color: var(--svg-color--e4c6ce, #E4C6CE);
}

.u4vr6me0r {
  stop-color: var(--svg-color--ab9c95, #AB9C95);
  stop-opacity: 0;
}

.ubqo6hdan {
  stop-color: var(--svg-color--a89b92, #A89B92);
  stop-opacity: 0;
}

.uciamrb7p {
  stop-color: var(--svg-color--988c82, #988C82);
}

.ui8rsxbiv {
  stop-color: var(--svg-color--c1acab, #C1ACAB);
}

.ullfjub9h {
  stop-color: var(--svg-color--e0c4ca, #E0C4CA);
}

.uupturd4r {
  stop-color: var(--svg-color--b9a2a4, #B9A2A4);
}

.v544b-bjz {
  stop-color: var(--svg-color--a3928d, #A3928D);
  stop-opacity: 0;
}

.va3c2jb6o {
  stop-color: var(--svg-color--b7a2a2, #B7A2A2);
  stop-opacity: 0;
}

.vhsp-dbci {
  stop-color: var(--svg-color--bda8a0, #BDA8A0);
  stop-opacity: 0;
}

.vhy6okbtl {
  stop-color: var(--svg-color--1e1e1e, #1E1E1E);
}

.vk-1kikqd {
  stop-color: var(--svg-color--cdb6b7, #CDB6B7);
}

.vk96cbccl {
  stop-color: var(--svg-color--1e1e1e, #1E1E1E);
  stop-opacity: 0;
}

.vqy_ltfen {
  fill: var(--svg-color--a69790, #A69790);
  d: path("M8.832 15.53v1.595c-.527.359-1.707 1.154-1.707 1.154s-1.071-.72-1.734-1.154l-1.13-3.873c-1.575-1.4-2.052-3.453.24-1.925c.57-.641 1.272-1.085 1.82-1.35c4.075 0 2.96 3.523 2.51 5.553");
}

.vstancbmp {
  stop-color: var(--svg-color--b39d9f, #B39D9F);
}

.vsyieqb8q {
  stop-color: var(--svg-color--ac9c94, #AC9C94);
}

.w1tgf338g {
  stop-color: var(--svg-color--c1a8ad, #C1A8AD);
  stop-opacity: 0;
}

.w4d4ygbyx {
  stop-color: var(--svg-color--ccb6b4, #CCB6B4);
  stop-opacity: 0;
}

.wdfb-pb5p {
  stop-color: var(--svg-color--c3adad, #C3ADAD);
}

.wfx_lguae {
  stop-color: var(--svg-color--cfbeb4, #CFBEB4);
}

.wgdo-tbkk {
  stop-color: var(--svg-color--c5b2ac, #C5B2AC);
}

.wilaomb7m {
  stop-color: var(--svg-color--8c7b7c, #8C7B7C);
}

.wl1g7-bgs {
  stop-color: var(--svg-color--c0a7ac, #C0A7AC);
}

.wpis97b1y {
  d: path("M7.174 19.024a1.65 1.65 0 0 1-1.576-1.188l-.215-.736H8.83v.276a1.65 1.65 0 0 1-1.642 1.648z");
}

.wq7v22g_t {
  d: path("M23.078 8.68a.71.71 0 0 1-.7.72a.71.71 0 0 1-.7-.72c0-.254.128-.477.322-.605a.7.7 0 0 1 .378-.114c.387 0 .7.322.7.72");
}

.wuk_avbmq {
  stop-color: var(--svg-color--252326, #252326);
}

.x1a0zqblh {
  stop-color: var(--svg-color--b99fa7, #B99FA7);
}

.x5d2yo15t {
  stop-color: var(--svg-color--cfb1bc, #CFB1BC);
  stop-opacity: 0;
}

.x8b-e-d1e {
  stop-color: var(--svg-color--af9b9a, #AF9B9A);
}

.xbbmtxopf {
  stop-color: var(--svg-color--988b82, #988B82);
}

.xdiz5bkvn {
  stop-color: var(--svg-color--dbb0d0, #DBB0D0);
}

.xfw4zrbps {
  d: path("M8.832 15.53v1.595c-.527.359-1.707 1.154-1.707 1.154s-1.071-.72-1.734-1.154l-1.13-3.873c-1.575-1.4-2.052-3.453.24-1.925c.57-.641 1.272-1.085 1.82-1.35c4.075 0 2.96 3.523 2.51 5.553");
}

.xkezcve6m {
  stop-color: var(--svg-color--b09d9d, #B09D9D);
}

.xvtv7ccem {
  fill-rule: evenodd;
  d: path("M26.01 4.733a.48.48 0 0 1 0 .68l-3.028 3.028h2.106c.528 0 .84.523.683.962h-3.37a.722.722 0 0 1-.51-1.232l3.438-3.438a.48.48 0 0 1 .68 0");
}

.xx8-k_svk {
  stop-color: var(--svg-color--d3bcbd, #D3BCBD);
}

.xxe7bw5id {
  stop-color: var(--svg-color--847179, #847179);
}

.xzxiu9vrp {
  stop-color: var(--svg-color--d5bebe, #D5BEBE);
  stop-opacity: 0;
}

.y_n4-hb7l {
  stop-color: var(--svg-color--c8b7ae, #C8B7AE);
  stop-opacity: 0;
}

.y3bk2ibki {
  stop-color: var(--svg-color--cab3b4, #CAB3B4);
}

.y7790bcck {
  stop-color: var(--svg-color--92847e, #92847E);
}

.y7r8hibxu {
  stop-color: var(--svg-color--91778b, #91778B);
}

.y8icfotyz {
  stop-color: var(--svg-color--9e9187, #9E9187);
  stop-opacity: 0;
}

.yaigewmgp {
  stop-color: var(--svg-color--8f7982, #8F7982);
}

.ylvonurqj {
  stop-color: var(--svg-color--dfcac5, #DFCAC5);
}

.z4ry93xoo {
  fill-rule: evenodd;
  d: path("m8.834 25.854l.001.962c0 .266.216.48.481.48h.962a.48.48 0 0 0 .481-.481l-.002-.962z");
}

.z53hbcbjw {
  stop-color: var(--svg-color--86777d, #86777D);
  stop-opacity: 0;
}

.zekaiwv8e {
  stop-color: var(--svg-color--6e6e6e, #6E6E6E);
}

.zgdh8b08u {
  d: path("M23.094 17.559h-.14a2.63 2.63 0 0 1-1.91-.824c-.94-.996-.94-2.563-.024-3.58a2.7 2.7 0 0 1 1.987-.889h.258l.696-1.392a.96.96 0 0 1 .86-.532h4.698a.48.48 0 0 1 .481.48v.963a.48.48 0 0 1-.48.481h-1.397a.96.96 0 0 0-.812.446l-2.476 3.89a2.07 2.07 0 0 1-1.741.956");
}

.zj-80qbav {
  stop-color: var(--svg-color--876f84, #876F84);
}

.znevj04kj {
  stop-color: var(--svg-color--b29fb0, #B29FB0);
}

.zt5bgcbxe {
  stop-color: var(--svg-color--cca5c1, #CCA5C1);
}

.ztzwxpnbl {
  stop-color: var(--svg-color--cdb9b5, #CDB9B5);
}

.zuewshudh {
  d: path("m8.836 25.856l-.005-3.51c0-.255.1-.499.279-.68l2.621-2.64s1.3-.282 1.988.474s.274 1.5.274 1.5l-2.866 2.232a.96.96 0 0 0-.371.762l.004 1.86a.48.48 0 0 1-.481.482h-.962a.48.48 0 0 1-.481-.48");
}

.zz_0etkgu {
  stop-color: var(--svg-color--1d1a18, #1D1A18);
}

</style>
