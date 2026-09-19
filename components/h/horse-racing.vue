<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="g8hojttzg"/><g filter="url(#ifTsKYx)"><path fill="url(#iqrVLle)" class="gt4x63mzn"/></g><path fill="url(#iM7OIGd)" class="bd905wbdc"/><path fill="url(#iXulckb)" class="tv37hulzl"/><path fill="url(#i4xmBid)" class="tv37hulzl"/><path fill="url(#iotSjBd)" class="tv37hulzl"/><path fill="url(#ilh154K)" class="tv37hulzl"/><path fill="url(#iJ7kVex)" class="tv37hulzl"/><path fill="url(#ihbTlTc)" class="tv37hulzl"/><path fill="url(#iL7nNzc)" class="tv37hulzl"/><path fill="url(#iIjn9cS)" class="tv37hulzl"/><path fill="url(#ia4gtCc)" class="tv37hulzl"/><path fill="url(#iTT85De)" class="tv37hulzl"/><path fill="url(#ipr0j6d)" class="tv37hulzl"/><path fill="url(#iOlmv0b)" class="v3__gxa3g"/><path fill="url(#iQRdWkc)" class="v3__gxa3g"/><g filter="url(#iiSxO5d)"><path fill="url(#iKsbdKd)" class="q9l62bb8x"/><path fill="url(#i8QfoGb)" class="q9l62bb8x"/></g><g filter="url(#iNQkcOd)"><path fill="url(#it1N8yd)" class="njiyxv81p"/><path fill="url(#ivZ3iVd)" class="njiyxv81p"/><path fill="url(#iaoWWnG)" class="njiyxv81p"/></g><g filter="url(#iISZy8b)"><path stroke="url(#iUcGjOb)" class="okbwubcjd"/></g><g filter="url(#ibLlxCc)"><path fill="url(#ikvzLad)" class="l_ws6qfkw"/><path fill="url(#iRrAJNc)" class="l_ws6qfkw"/><path fill="url(#imtzDJe)" class="l_ws6qfkw"/><path fill="url(#iRiytXc)" class="l_ws6qfkw"/><path fill="url(#ix0l7BG)" class="l_ws6qfkw"/><path fill="url(#icoCG3A)" class="l_ws6qfkw"/><path fill="url(#iYpzDte)" class="l_ws6qfkw"/><path fill="url(#iK7cunu)" class="l_ws6qfkw"/><path fill="url(#itu7s1d)" class="l_ws6qfkw"/><path fill="url(#i0g34Ee)" class="l_ws6qfkw"/></g><g filter="url(#ibLlxCc)"><path fill="url(#ikvzLad)" class="l_ws6qfkw"/><path fill="url(#iRrAJNc)" class="l_ws6qfkw"/><path fill="url(#imtzDJe)" class="l_ws6qfkw"/><path fill="url(#iRiytXc)" class="l_ws6qfkw"/><path fill="url(#ix0l7BG)" class="l_ws6qfkw"/><path fill="url(#icoCG3A)" class="l_ws6qfkw"/><path fill="url(#iYpzDte)" class="l_ws6qfkw"/><path fill="url(#iK7cunu)" class="l_ws6qfkw"/><path fill="url(#itu7s1d)" class="l_ws6qfkw"/><path fill="url(#i0g34Ee)" class="l_ws6qfkw"/></g><path fill="url(#ijiq2GG)" class="elia8sbte"/><path fill="url(#iOMnDRb)" class="elia8sbte"/><circle fill="url(#ivl1AKb)" class="buhz9kcxm"/><circle fill="url(#i3V12Sb)" class="buhz9kcxm"/><circle fill="url(#idPGZFd)" class="buhz9kcxm"/><g filter="url(#iXYa4Pc)"><path fill="url(#ivtNoke)" class="zcrg57tqr"/></g><g filter="url(#im7s2jR)"><path class="vy6j7ybke"/></g><g filter="url(#i1vDAyL)"><path fill="url(#iOvo6Oe)" class="yywx__qpz"/></g><g filter="url(#ivOBHPc)"><path fill="url(#iSACTKN)" class="k9vdi6_ad"/></g><g filter="url(#ihZNcmr)"><path class="i9mqu9s6x"/></g><g filter="url(#iDYJixe)"><path stroke="url(#iaxIy7c)" class="gtgf8ebyn"/></g><g filter="url(#iO47xqb)"><path fill="url(#idZKpDw)" class="eu9yqcb3q"/></g><g filter="url(#iHX99Hb)"><path stroke="url(#idxQbme)" class="ro6jv7b4p"/></g><g filter="url(#iXTlwUd)"><path stroke="url(#izHEJNd)" class="wqrxl6bcm"/></g><g filter="url(#iJtr4Ic)"><path class="x23z-v13r"/></g><g filter="url(#i3VPkfe)"><path fill="url(#iaKV7gb)" class="ptd201t9v"/></g><g clip-rule="evenodd" filter="url(#ixylOKE)" class="d2kvgvbvc"><path fill="url(#iEI2E2x)" class="hhrd9xzum"/><path fill="url(#iZjOzEs)" class="hhrd9xzum"/></g><g filter="url(#iRcnfmc)"><path fill="url(#iBh3afd)" class="aeuwu8b1i"/><path fill="url(#izZYl8c)" class="aeuwu8b1i"/></g><g filter="url(#iBvXZfe)"><path class="cvremvnqx"/></g><path fill="url(#iRpSY2c)" class="u6s_5wbvu"/><g filter="url(#iiVxj5c)"><path class="iix6sgbdo"/><path fill="url(#ioE6F2b)" class="bbba1xbte"/></g><path fill="url(#iGkYW1t)" class="bbba1xbte"/><g filter="url(#imJ96ze)"><path fill="url(#ic70V1b)" class="ddhf19xaw"/><path fill="url(#iI3Oo2d)" class="ddhf19xaw"/></g><g filter="url(#ixEAvnb)"><path fill="url(#ii95KYR)" class="sio64nb-w"/><path fill="url(#iGRUCyd)" class="sio64nb-w"/></g><g filter="url(#i0feqVc)"><path class="x8jpsgu1y"/></g><g filter="url(#i8Z5ZPd)"><path fill="url(#izjqXdm)" class="wo8d4bchi"/></g><g filter="url(#iyhZoDd)"><path class="uuu5cbc7v"/><path fill="url(#ilP21wc)" class="gq9vbu_qj"/></g><path fill="url(#ircgtZc)" class="rrlqfnbcn"/><path class="phvhos7lq"/><path class="bv8simb9r"/><path class="wae82lo1m"/><path class="ld_ehebzj"/><path class="lgi9jhb3u"/><path fill="url(#ic4UH0b)" class="zn8a0d6yz"/><path fill="url(#iXgOXOe)" class="zn8a0d6yz"/><path fill="url(#ieJwS2b)" class="zn8a0d6yz"/><path fill="url(#i8tbHye)" class="xvaoujpwx"/><path fill="url(#ikxP5DL)" class="xvaoujpwx"/><path fill="url(#iE86pcd)" class="xvaoujpwx"/><path clip-rule="evenodd" class="j0ji1ibsj"/><defs><radialGradient id="iqrVLle" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 1.32812 -1.34623 2.34402 26.594 9.484)" gradientUnits="userSpaceOnUse"><stop class="y28nttbhx"/><stop offset="1" class="g_sgy9b-w"/></radialGradient><radialGradient id="iXulckb" cx="0" cy="0" r="1" gradientTransform="rotate(145.981 7.877 6.186)scale(3.88535 7.30852)" gradientUnits="userSpaceOnUse"><stop class="i_7zxhbsi"/><stop offset="1" class="gzh6kscpy"/></radialGradient><radialGradient id="i4xmBid" cx="0" cy="0" r="1" gradientTransform="rotate(66.125 3.491 9.826)scale(10.4232 11.078)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="mwhyxzyic"/><stop offset="1" class="b7v57abyz"/></radialGradient><radialGradient id="ilh154K" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51143 1.89659 -1.12444 -.89608 13.621 4.307)" gradientUnits="userSpaceOnUse"><stop class="g2wc55b_k"/><stop offset="1" class="natse864u"/></radialGradient><radialGradient id="iJ7kVex" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52564 2.11911 -.89939 -1.07193 16.01 7.1)" gradientUnits="userSpaceOnUse"><stop class="g2wc55b_k"/><stop offset="1" class="natse864u"/></radialGradient><radialGradient id="ihbTlTc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34375 1.64062 -.26724 -.38178 17.938 7.89)" gradientUnits="userSpaceOnUse"><stop offset=".031" class="g2wc55b_k"/><stop offset=".893" class="natse864u"/></radialGradient><radialGradient id="iL7nNzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3281 2.53127 -.41232 -.37923 14.063 2.797)" gradientUnits="userSpaceOnUse"><stop class="g2wc55b_k"/><stop offset="1" class="natse864u"/></radialGradient><radialGradient id="iIjn9cS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.16972 .91894 -.40706 -.96112 14.776 4.894)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="ia4gtCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8234 .76563 -.34493 -.37095 13.43 4.727)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="iTT85De" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35937 1.21875 -.54907 -1.06294 16.422 7.875)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="ipr0j6d" cx="0" cy="0" r="1" gradientTransform="rotate(134.683 6.148 6.897)scale(1.99982 .95664)" gradientUnits="userSpaceOnUse"><stop class="bf8pxkoqd"/><stop offset="1" class="v-z8ul8_r"/></radialGradient><radialGradient id="iOlmv0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.89151 -1.62856 .98904 1.14873 3.887 4.629)" gradientUnits="userSpaceOnUse"><stop class="v0lxwrw8c"/><stop offset="1" class="qvruwibmg"/></radialGradient><radialGradient id="iQRdWkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8601 -.8015 .96609 -2.24205 5.667 5.008)" gradientUnits="userSpaceOnUse"><stop offset=".84" class="ul8ntc5jf"/><stop offset="1" class="gyskztbxs"/></radialGradient><radialGradient id="i8QfoGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.85156 2.14227 0 17.982 28.14)" gradientUnits="userSpaceOnUse"><stop class="esdhshb7o"/><stop offset="1" class="zk7_jm-pn"/></radialGradient><radialGradient id="ivZ3iVd" cx="0" cy="0" r="1" gradientTransform="rotate(-135 7.461 10.456)scale(1.01647 2.0084)" gradientUnits="userSpaceOnUse"><stop class="ufjhytbyb"/><stop offset="1" class="zk7_jm-pn"/></radialGradient><radialGradient id="iaoWWnG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5703 -1.52344 1.11774 -1.15213 6.797 18.781)" gradientUnits="userSpaceOnUse"><stop class="lhxz0tb6k"/><stop offset="1" class="t7se8-bri"/></radialGradient><radialGradient id="iRrAJNc" cx="0" cy="0" r="1" gradientTransform="rotate(-106.39 14.446 9.47)scale(6.64502 8.99011)" gradientUnits="userSpaceOnUse"><stop class="cqi1m2bxr"/><stop offset="1" class="wb8annbpt"/></radialGradient><radialGradient id="imtzDJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.875 6.53125 0 16.282 21.25)" gradientUnits="userSpaceOnUse"><stop class="k_uo2lb7f"/><stop offset="1" class="wm54im16m"/></radialGradient><radialGradient id="iRiytXc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.418 29.35 -6.37)scale(2.36222 5.41084)" gradientUnits="userSpaceOnUse"><stop class="k_uo2lb7f"/><stop offset="1" class="wm54im16m"/></radialGradient><radialGradient id="ix0l7BG" cx="0" cy="0" r="1" gradientTransform="rotate(-16.631 49.975 -13.224)scale(5.0226 10.8354)" gradientUnits="userSpaceOnUse"><stop class="r7nt8bqar"/><stop offset="1" class="n0earqbbn"/></radialGradient><radialGradient id="icoCG3A" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -1.51562 .69875 1.1958 4.969 8.766)" gradientUnits="userSpaceOnUse"><stop class="q92bisbnd"/><stop offset="1" class="j1hbibbxu"/></radialGradient><radialGradient id="iYpzDte" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .42969 -1.30182 2.03557 6 2.79)" gradientUnits="userSpaceOnUse"><stop class="zbcn3kg0t"/><stop offset="1" class="nz41ibb3u"/></radialGradient><radialGradient id="iK7cunu" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -1.42187 6.45399 2.62414 9.735 25.828)" gradientUnits="userSpaceOnUse"><stop class="i73baob2a"/><stop offset="1" class="ziz970b6i"/></radialGradient><radialGradient id="itu7s1d" cx="0" cy="0" r="1" gradientTransform="rotate(121.088 -1.26 14.94)scale(.62034 2.32909)" gradientUnits="userSpaceOnUse"><stop class="i7kwnsbtw"/><stop offset="1" class="ozl41i9iy"/></radialGradient><radialGradient id="i0g34Ee" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.67188 .2791 .44138 8.266 19.406)" gradientUnits="userSpaceOnUse"><stop class="w0qioubuo"/><stop offset="1" class="b89-4bbfl"/></radialGradient><radialGradient id="iOMnDRb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4422 -.80985 .22471 .40017 2.406 8.523)" gradientUnits="userSpaceOnUse"><stop class="lagn3cb8q"/><stop offset="1" class="r8bvzmz9u"/></radialGradient><radialGradient id="ivl1AKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.144 5.85)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i3V12Sb" cx="0" cy="0" r="1" gradientTransform="rotate(137.926 1.959 4.132)scale(.3074 .27043)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iZjOzEs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8125 0 0 -1.72813 11.048 11.666)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="oteylfbgl"/><stop offset="1" class="v_6b5hdqf"/></radialGradient><radialGradient id="izZYl8c" cx="0" cy="0" r="1" gradientTransform="scale(5.97427 5.37791)rotate(90 .5 2.707)" gradientUnits="userSpaceOnUse"><stop class="d7245_k1i"/><stop offset="1" class="y3ft0hbqe"/></radialGradient><radialGradient id="ioE6F2b" cx="0" cy="0" r="1" gradientTransform="matrix(4.48914 -3 2.4944 3.73256 19.08 10.313)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="d2g4ymxaw"/><stop offset=".846" class="u_g7lj_om"/></radialGradient><radialGradient id="iGkYW1t" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 3.70312 19.704 8)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="s_8bwbbxs"/><stop offset="1" class="bmmjo61nq"/></radialGradient><radialGradient id="iI3Oo2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.54688 2.1875 0 19.29 16.406)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="plwo-m4rc"/><stop offset="1" class="ofm90pbgb"/></radialGradient><radialGradient id="ilP21wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .73438 -2.1875 0 15.595 3.969)" gradientUnits="userSpaceOnUse"><stop class="l7pwk4r4g"/><stop offset="1" class="scfcuhb5w"/></radialGradient><radialGradient id="ircgtZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45312 .60938 -.50662 -.37672 15.509 4.93)" gradientUnits="userSpaceOnUse"><stop class="bbec10bde"/><stop offset="1" class="o2pej7bcj"/></radialGradient><radialGradient id="ic4UH0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03349 -.60938 0 15.439 5.482)" gradientUnits="userSpaceOnUse"><stop class="f85dnpc-e"/><stop offset="1" class="zv6ipnb4d"/></radialGradient><radialGradient id="ieJwS2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7627 -.35217 0 15.275 5.024)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="f-3e7z_oy"/><stop offset="1" class="pw72fac7r"/></radialGradient><radialGradient id="i8tbHye" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34375 0 0 -1.45351 16.048 4.188)" gradientUnits="userSpaceOnUse"><stop class="pjmnsjz9j"/><stop offset="1" class="nxnrjizns"/></radialGradient><radialGradient id="iE86pcd" cx="0" cy="0" r="1" gradientTransform="matrix(.51855 0 0 .40625 12.06 3.703)" gradientUnits="userSpaceOnUse"><stop class="j54opgy7g"/><stop offset="1" class="ttkfwetcv"/></radialGradient><linearGradient id="iM7OIGd" x1="1.743" x2="6.067" y1="9.534" y2="6.043" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ixz6v2bhs"/><stop offset="1" class="e2a7rcbkj"/></linearGradient><linearGradient id="iotSjBd" x1="14.384" x2="11.506" y1="7.53" y2="9.24" gradientUnits="userSpaceOnUse"><stop offset=".516" class="mwhyxzyic"/><stop offset="1" class="b7v57abyz"/></linearGradient><linearGradient id="iKsbdKd" x1="20.906" x2="15.67" y1="19.438" y2="21.538" gradientUnits="userSpaceOnUse"><stop class="kedgnpb4s"/><stop offset="1" class="j3lv25bwc"/></linearGradient><linearGradient id="it1N8yd" x1="7.991" x2="2.993" y1="16.969" y2="22" gradientUnits="userSpaceOnUse"><stop class="j5i0bcbpv"/><stop offset="1" class="j3lv25bwc"/></linearGradient><linearGradient id="iUcGjOb" x1="4.745" x2="8.307" y1="19.764" y2="17.436" gradientUnits="userSpaceOnUse"><stop class="bd746ob-n"/><stop offset="1" class="aj7oio2ey"/></linearGradient><linearGradient id="ikvzLad" x1="8.558" x2="21.246" y1="1.981" y2="26.37" gradientUnits="userSpaceOnUse"><stop class="d3ukzf59w"/><stop offset="1" class="pp6wxobfe"/></linearGradient><linearGradient id="ijiq2GG" x1="2.891" x2="3.608" y1="8.047" y2="9.689" gradientUnits="userSpaceOnUse"><stop offset=".006" class="zyl7mobjg"/><stop offset="1" class="oksaimbfl"/></linearGradient><linearGradient id="idPGZFd" x1="5.897" x2="5.553" y1="5.619" y2="5.4" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ivtNoke" x1="18.15" x2="21.549" y1="27.031" y2="21.674" gradientUnits="userSpaceOnUse"><stop class="a8w_-db0v"/><stop offset="1" class="c0836bb1j"/></linearGradient><linearGradient id="iOvo6Oe" x1="7.901" x2="14.232" y1="3.63" y2="13.969" gradientUnits="userSpaceOnUse"><stop class="l6asi_bad"/><stop offset="1" class="caccqtb0a"/></linearGradient><linearGradient id="iSACTKN" x1="28.938" x2="25.719" y1="12.748" y2="24.781" gradientUnits="userSpaceOnUse"><stop class="s2jmff1mi"/><stop offset="1" class="g-w90zbbh"/></linearGradient><linearGradient id="iaxIy7c" x1="27.5" x2="21.282" y1="19.188" y2="33.063" gradientUnits="userSpaceOnUse"><stop class="g-w90zbbh"/><stop offset=".239" class="s2jmff1mi"/><stop offset="1" class="g-w90zbbh"/></linearGradient><linearGradient id="idZKpDw" x1="7.375" x2="8.891" y1="2.75" y2="5.625" gradientUnits="userSpaceOnUse"><stop class="t5ng6m5ia"/><stop offset="1" class="neuu31bdt"/></linearGradient><linearGradient id="idxQbme" x1="9.375" x2="10.156" y1="24.219" y2="17.781" gradientUnits="userSpaceOnUse"><stop class="wi-b97b3f"/><stop offset="1" class="vsm9a27iv"/></linearGradient><linearGradient id="izHEJNd" x1="7.016" x2="8.011" y1="21.844" y2="21.983" gradientUnits="userSpaceOnUse"><stop class="wi-b97b3f"/><stop offset="1" class="vsm9a27iv"/></linearGradient><linearGradient id="iaKV7gb" x1="8.691" x2="8.691" y1="3.632" y2="10.773" gradientUnits="userSpaceOnUse"><stop class="vk0ei6bvx"/><stop offset="1" class="a2vgvxbzr"/></linearGradient><linearGradient id="iEI2E2x" x1="3.611" x2="9.298" y1="6.531" y2="12.406" gradientUnits="userSpaceOnUse"><stop class="zq6nalbhy"/><stop offset="1" class="b3oa5abtt"/></linearGradient><linearGradient id="iBh3afd" x1="23.954" x2="14.162" y1="14.969" y2="14.969" gradientUnits="userSpaceOnUse"><stop class="izbdogb6w"/><stop offset="1" class="h85cnk7bk"/></linearGradient><linearGradient id="iRpSY2c" x1="16.048" x2="15.048" y1="6.312" y2="7.328" gradientUnits="userSpaceOnUse"><stop class="kj1xf7bps"/><stop offset="1" class="bibp9_mtz"/></linearGradient><linearGradient id="ic70V1b" x1="20.111" x2="19.201" y1="15.344" y2="15.344" gradientUnits="userSpaceOnUse"><stop class="n41jlck8d"/><stop offset="1" class="f3wb6bbjn"/></linearGradient><linearGradient id="ii95KYR" x1="18.892" x2="12.079" y1="7.125" y2="12.75" gradientUnits="userSpaceOnUse"><stop class="q03-9xl3z"/><stop offset="1" class="evtjoobph"/></linearGradient><linearGradient id="iGRUCyd" x1="18.736" x2="18.736" y1="5.875" y2="7.344" gradientUnits="userSpaceOnUse"><stop offset=".106" class="vjbpvrbhq"/><stop offset="1" class="f20ju_bwg"/></linearGradient><linearGradient id="izjqXdm" x1="12.829" x2="15.61" y1="5.594" y2="5.594" gradientUnits="userSpaceOnUse"><stop class="fdjlyeazd"/><stop offset="1" class="mz70ux43u"/></linearGradient><linearGradient id="iXgOXOe" x1="14.922" x2="14.922" y1="4.094" y2="4.656" gradientUnits="userSpaceOnUse"><stop class="mq29_7dze"/><stop offset="1" class="cyp9wj1oc"/></linearGradient><linearGradient id="ikxP5DL" x1="15.439" x2="15.439" y1="4.188" y2="3.961" gradientUnits="userSpaceOnUse"><stop offset=".104" class="bzycneplr"/><stop offset="1" class="zp3ya6bcy"/></linearGradient><filter id="ifTsKYx" width="6.656" height="9.594" x="23.813" y="4.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".5"/></filter><filter id="iiSxO5d" width="6.296" height="12.775" x="16.979" y="15.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.415686 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="iNQkcOd" width="10.145" height="7.53" x="2.993" y="15.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.415686 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="iISZy8b" width="4.887" height="6.419" x="3.551" y="16.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".2"/></filter><filter id="ibLlxCc" width="25.963" height="28.25" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.262745 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="iXYa4Pc" width="5.609" height="7.813" x="16.985" y="20.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".5"/></filter><filter id="im7s2jR" width="4.951" height="7.809" x="16.911" y="6.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.380392 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="i1vDAyL" width="8.632" height="13.516" x="5.891" y="1.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".5"/></filter><filter id="ivOBHPc" width="9.063" height="15.783" x="20.125" y="10.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation="1"/></filter><filter id="ihZNcmr" width="6.629" height="3.566" x="9.25" y="9.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".5"/></filter><filter id="iDYJixe" width="5.635" height="14.06" x="22.491" y="16.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".5"/></filter><filter id="iO47xqb" width="2.594" height="3.469" x="6.547" y="2.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".125"/></filter><filter id="iHX99Hb" width="4.564" height="6.385" x="7.436" y="19.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".25"/></filter><filter id="iXTlwUd" width="1.13" height="3.282" x="6.959" y="20.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".125"/></filter><filter id="iJtr4Ic" width="5.031" height="13.344" x="5.891" y="6.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".5"/></filter><filter id="i3VPkfe" width="1.073" height="7.76" x="8.14" y="3.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.03" dy=".03"/><feGaussianBlur stdDeviation=".03"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.870588 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="ixylOKE" width="9.046" height="5.805" x="3.209" y="5.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.03" dy=".03"/><feGaussianBlur stdDeviation=".03"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.870588 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="iRcnfmc" width="10.084" height="6.813" x="14.062" y="11.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.862745 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="iBvXZfe" width="4.398" height="5.966" x="16.911" y="11.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22600" stdDeviation=".325"/></filter><filter id="iiVxj5c" width="5.87" height="10.298" x="17.899" y="6.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.780392 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.47451 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22600" result="effect2_innerShadow_3987_22600"/></filter><filter id="imJ96ze" width="2.504" height="2.862" x="18.049" y="13.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.243137 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="ixEAvnb" width="9.648" height="6.225" x="10.517" y="5.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.35"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.223529 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="i0feqVc" width="1.826" height="2.156" x="10.508" y="9.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.35"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.513726 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="i8Z5ZPd" width="4.259" height="4.664" x="12.104" y="2.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.494118 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/></filter><filter id="iyhZoDd" width="4.06" height="3.382" x="12.986" y="3.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.772549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.411765 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22600" result="effect2_innerShadow_3987_22600"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:horse-racing" /></template>
<style>
.a2vgvxbzr {
  stop-color: var(--svg-color--4cbf8d, #4CBF8D);
}

.a8w_-db0v {
  stop-color: var(--svg-color--82585e, #82585E);
}

.aeuwu8b1i {
  d: path("m14.162 11.297l1.143.368c.495.16 1.013.241 1.533.241h7.208a.1.1 0 0 1 .1.1v5.103a1 1 0 0 1-1 1h-7.984a1 1 0 0 1-1-1z");
}

.aj7oio2ey {
  stop-color: var(--svg-color--876363, #876363);
  stop-opacity: 0;
}

.b3oa5abtt {
  stop-color: var(--svg-color--47b788, #47B788);
}

.b7v57abyz {
  stop-color: var(--svg-color--1e1818, #1E1818);
}

.b89-4bbfl {
  stop-color: var(--svg-color--97716c, #97716C);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bbba1xbte {
  d: path("M23.568 8.42c-.03-1.238-1.066-2.202-2.304-2.202h-1.36v4.262l-.698.537a2.27 2.27 0 0 0-.66 1.604v1.735c0 .345-.071.69-.203 1.015l-.274.639a.254.254 0 0 0 .233.355H20.1a.25.25 0 0 0 .253-.253V12.63c0-.122.051-.233.132-.325l2.282-2.11q.138-.108.244-.244a2.23 2.23 0 0 0 .558-1.532");
}

.bbec10bde {
  stop-color: var(--svg-color--fdc442, #FDC442);
}

.bd746ob-n {
  stop-color: var(--svg-color--876363, #876363);
}

.bd905wbdc {
  d: path("M2.998 6.918c-.336.363-.739.78-.739.78c-.22.256-.31.605-.231.945c.155.675.839 1.008 1.48.75l.77-.311z");
}

.bf8pxkoqd {
  stop-color: var(--svg-color--343435, #343435);
}

.bibp9_mtz {
  stop-color: var(--svg-color--c0882b, #C0882B);
}

.bmmjo61nq {
  stop-color: var(--svg-color--d6c8e5, #D6C8E5);
  stop-opacity: 0;
}

.buhz9kcxm {
  cx: 5.995px;
  cy: 6.012px;
  r: 0.5px;
}

.bv8simb9r {
  fill: var(--svg-color--58403c, #58403C);
  d: path("M12.984 5.122c-.01-.04-.02-.071-.02-.122c0-.183.111-.335.264-.335c.142 0 .264.152.264.335c0 .04-.01.081-.02.122z");
}

.bzycneplr {
  stop-color: var(--svg-color--6c4ba9, #6C4BA9);
}

.c0836bb1j {
  stop-color: var(--svg-color--82585e, #82585E);
  stop-opacity: 0;
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.caccqtb0a {
  stop-color: var(--svg-color--ab8073, #AB8073);
  stop-opacity: 0;
}

.cqi1m2bxr {
  stop-color: var(--svg-color--6a433b, #6A433B);
}

.cvremvnqx {
  fill: var(--svg-color--338469, #338469);
  d: path("M20.66 11.994h-2.455c-.153.311-.146.569-.146.92v1.736c0 .345-.071.69-.203 1.015l-.274.64a.254.254 0 0 0 .233.354h1.796a.25.25 0 0 0 .254-.253v-3.481c0-.122.05-.233.132-.325z");
}

.cyp9wj1oc {
  stop-color: var(--svg-color--4e3886, #4E3886);
  stop-opacity: 0;
}

.d2g4ymxaw {
  stop-color: var(--svg-color--d6c8e3, #D6C8E3);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d3ukzf59w {
  stop-color: var(--svg-color--925f52, #925F52);
}

.d7245_k1i {
  stop-color: var(--svg-color--3da97e, #3DA97E);
}

.ddhf19xaw {
  d: path("M18.547 13.503v.853c0 .345-.072.69-.203 1.015l-.274.639a.254.254 0 0 0 .233.355h1.796a.25.25 0 0 0 .254-.254v-2.608z");
}

.e2a7rcbkj {
  stop-color: var(--svg-color--ffdea7, #FFDEA7);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.elia8sbte {
  d: path("m4.197 9.114l-1.26-2.13l-.653.71a1.07 1.07 0 0 0-.262.939c.14.687.82 1.028 1.469.765z");
}

.esdhshb7o {
  stop-color: var(--svg-color--794562, #794562);
}

.eu9yqcb3q {
  d: path("M7.985 5.422L6.797 2.453l2.094 1.781z");
}

.evtjoobph {
  stop-color: var(--svg-color--7a63b7, #7A63B7);
}

.f-3e7z_oy {
  stop-color: var(--svg-color--603c71, #603C71);
}

.f20ju_bwg {
  stop-color: var(--svg-color--7468a1, #7468A1);
  stop-opacity: 0;
}

.f3wb6bbjn {
  stop-color: var(--svg-color--32253e, #32253E);
}

.f85dnpc-e {
  stop-color: var(--svg-color--8e77c8, #8E77C8);
}

.fdjlyeazd {
  stop-color: var(--svg-color--fab53d, #FAB53D);
}

.ft5dv1b6b {
  fill: none;
}

.g_sgy9b-w {
  stop-color: var(--svg-color--535254, #535254);
}

.g-w90zbbh {
  stop-color: var(--svg-color--a47c71, #A47C71);
  stop-opacity: 0;
}

.g2wc55b_k {
  stop-color: var(--svg-color--5a5a5b, #5A5A5B);
}

.g8hojttzg {
  fill: var(--svg-color--292727, #292727);
  d: path("M28.003 6.648V5.485c0-.268.217-.485.485-.485C29.323 5 30 5.678 30 6.514v1.989c0 1.38-1.118 2.5-2.497 2.5H26.35a.356.356 0 0 0-.355.356V16h-1.998V9.504c0-1.38 1.118-2.5 2.497-2.5h1.154c.196 0 .356-.16.356-.356");
}

.gq9vbu_qj {
  d: path("M16.353 5.69s.751-.508.487-1.634c-.182-.01-.152.04-.314-.05c-.518-.275-1.045-.539-1.563-.802a1 1 0 0 1-.142.04c-.568.122-1.126.274-1.684.447c.192.091.466.142.832.142c1.156 0 1.156.7 1.156.7s.477-.122.477 1.309c0 .74.558.578.822.578c.437.01.508-.73-.07-.73");
}

.gt4x63mzn {
  d: path("M28.719 5.688v1.875h-1.906a2 2 0 0 0-2 2v3.718h.61v-2.937h2.046a2 2 0 0 0 2-2V6.813c0-.493-.296-.936-.75-1.125");
}

.gtgf8ebyn {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.688 29.188l2.554-3.281a3 3 0 0 0 .633-1.843V17.28");
}

.gyskztbxs {
  stop-color: var(--svg-color--4a494a, #4A494A);
}

.gzh6kscpy {
  stop-color: var(--svg-color--363335, #363335);
}

.h85cnk7bk {
  stop-color: var(--svg-color--42bc88, #42BC88);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hhrd9xzum {
  d: path("M7.013 10.972L3.24 6.66l.703-.77l3.862 4.392a.98.98 0 0 0 .734.334h3.717v1.05H8.539a2.03 2.03 0 0 1-1.526-.694");
}

.i_7zxhbsi {
  stop-color: var(--svg-color--535253, #535253);
}

.i73baob2a {
  stop-color: var(--svg-color--633456, #633456);
}

.i7kwnsbtw {
  stop-color: var(--svg-color--6a463f, #6A463F);
}

.i9mqu9s6x {
  fill: var(--svg-color--69303b, #69303B);
  d: path("M10.25 11.692c0-.433.31-.783.694-.783h3.935v1.566h-3.935c-.383 0-.694-.351-.694-.783");
}

.iix6sgbdo {
  fill: var(--svg-color--d5c7e4, #D5C7E4);
  d: path("M23.568 8.42c-.03-1.238-1.066-2.202-2.304-2.202h-1.36v4.262l-.698.537a2.27 2.27 0 0 0-.66 1.604v1.735c0 .345-.071.69-.203 1.015l-.274.639a.254.254 0 0 0 .233.355H20.1a.25.25 0 0 0 .253-.253V12.63c0-.122.051-.233.132-.325l2.282-2.11q.138-.108.244-.244a2.23 2.23 0 0 0 .558-1.532");
}

.ixz6v2bhs {
  stop-color: var(--svg-color--dc872a, #DC872A);
}

.izbdogb6w {
  stop-color: var(--svg-color--3fc284, #3FC284);
}

.j0ji1ibsj {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M13.62 5.854c.03.028.033.075.006.106a.7.7 0 0 1-.27.18a.7.7 0 0 1-.227.048a.075.075 0 1 1 0-.15c.032 0 .098-.01.173-.038a.55.55 0 0 0 .212-.14a.075.075 0 0 1 .106-.006");
}

.j1hbibbxu {
  stop-color: var(--svg-color--6f3e55, #6F3E55);
  stop-opacity: 0;
}

.j3lv25bwc {
  stop-color: var(--svg-color--805655, #805655);
}

.j54opgy7g {
  stop-color: var(--svg-color--7668a3, #7668A3);
}

.j5i0bcbpv {
  stop-color: var(--svg-color--5a3933, #5A3933);
}

.k_uo2lb7f {
  stop-color: var(--svg-color--733b61, #733B61);
}

.k9vdi6_ad {
  d: path("M27.188 16.875c0-3.156-2.235-4.515-5.063-4.031v.781l1.05.651a3 3 0 0 1 1.419 2.55v4.987l2.594 2.718z");
}

.kedgnpb4s {
  stop-color: var(--svg-color--522a34, #522A34);
}

.kj1xf7bps {
  stop-color: var(--svg-color--ae621f, #AE621F);
}

.l_ws6qfkw {
  d: path("M23.05 12h-7.04A3.44 3.44 0 0 1 13 10.225L9.96 4.748c-.273-.492-.645-.828-1.112-1.195l-2.016-1.51a.27.27 0 0 0-.414.227v.83a.28.28 0 0 1-.076.195l-4.06 4.398a1.07 1.07 0 0 0-.261.94c.14.687.82 1.028 1.469.765l2.395-.966a.297.297 0 0 1 .405.235l1.11 8.045a4.95 4.95 0 0 0 1.031 2.413a.26.26 0 0 1-.019.348l-.641.643a2.65 2.65 0 0 0-.78 1.887a2.73 2.73 0 0 0 .812 1.911L9.05 25.17a2.8 2.8 0 0 0 2.003.83h.456a.48.48 0 0 0 .478-.479V24.48a.48.48 0 0 0-.478-.479h-.456a.84.84 0 0 1-.59-.244L9.2 22.483a.66.66 0 0 1-.016-.952l.88-.88a.26.26 0 0 1 .287-.056c.605.262 1.27.406 1.965.406h8.004c.425 0 .838.138 1.177.393l2.513 1.887a2.4 2.4 0 0 1 .48 3.36l-2.24 2.989a.232.232 0 0 0 .186.371h1.217c.2 0 .39-.091.515-.248l3.234-4.048a2.57 2.57 0 0 0 .562-1.604v-7.18a4.916 4.916 0 0 0-4.913-4.92");
}

.l6asi_bad {
  stop-color: var(--svg-color--ab8073, #AB8073);
}

.l7pwk4r4g {
  stop-color: var(--svg-color--bb6a1e, #BB6A1E);
}

.lagn3cb8q {
  stop-color: var(--svg-color--d7aa87, #D7AA87);
}

.ld_ehebzj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.356 5.016c.027-.005.042-.046.033-.092c-.01-.045-.039-.077-.066-.071c-.028.005-.042.046-.033.092c.009.045.039.077.066.071");
}

.lgi9jhb3u {
  fill: var(--svg-color--99303e, #99303E);
  d: path("M13.815 4.252a.098.098 0 0 1-.117.157h-.001l-.006-.005l-.028-.017a.8.8 0 0 0-.495-.102a.098.098 0 1 1-.022-.194a1 1 0 0 1 .654.15l.01.007l.003.003zm-.117.157");
}

.lhxz0tb6k {
  stop-color: var(--svg-color--5f3553, #5F3553);
}

.mq29_7dze {
  stop-color: var(--svg-color--4e3886, #4E3886);
}

.mwhyxzyic {
  stop-color: var(--svg-color--1e1818, #1E1818);
  stop-opacity: 0;
}

.mz70ux43u {
  stop-color: var(--svg-color--eaa433, #EAA433);
}

.n0earqbbn {
  stop-color: var(--svg-color--855f53, #855F53);
  stop-opacity: 0;
}

.n41jlck8d {
  stop-color: var(--svg-color--45424a, #45424A);
}

.natse864u {
  stop-color: var(--svg-color--5a5a5b, #5A5A5B);
  stop-opacity: 0;
}

.neuu31bdt {
  stop-color: var(--svg-color--9f7667, #9F7667);
  stop-opacity: 0;
}

.njiyxv81p {
  d: path("M4.753 23.417a.38.38 0 0 1-.538 0l-.392-.392a2.82 2.82 0 0 1-.83-2.005v-2.358a2.66 2.66 0 0 1 2.66-2.663h7.336v2H5.652a.66.66 0 0 0-.661.663v2.358c0 .221.088.434.244.59l.391.393a.38.38 0 0 1 0 .538z");
}

.nxnrjizns {
  stop-color: var(--svg-color--6e5ca2, #6E5CA2);
}

.nz41ibb3u {
  stop-color: var(--svg-color--926c60, #926C60);
  stop-opacity: 0;
}

.o2pej7bcj {
  stop-color: var(--svg-color--e09836, #E09836);
}

.ofm90pbgb {
  stop-color: var(--svg-color--2f293f, #2F293F);
  stop-opacity: 0;
}

.okbwubcjd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m4.901 22.373l-.194-.202a2 2 0 0 1-.556-1.384v-2.383c0-.69.56-1.25 1.25-1.25H7.84");
}

.oksaimbfl {
  stop-color: var(--svg-color--c47c8f, #C47C8F);
}

.oteylfbgl {
  stop-color: var(--svg-color--368666, #368666);
}

.ozl41i9iy {
  stop-color: var(--svg-color--6a463f, #6A463F);
  stop-opacity: 0;
}

.phvhos7lq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.061 5.122c-.049 0-.088-.051-.097-.112V5c0-.254.204-.396.409-.396c.195 0 .41.142.41.396v.01c0 .06-.04.112-.098.112z");
}

.pjmnsjz9j {
  stop-color: var(--svg-color--9684cd, #9684CD);
}

.plwo-m4rc {
  stop-color: var(--svg-color--2f293f, #2F293F);
}

.pp6wxobfe {
  stop-color: var(--svg-color--8a525a, #8A525A);
}

.ptd201t9v {
  d: path("M8.17 3.043v7.73h1.043V3.867a8 8 0 0 0-.466-.391z");
}

.pw72fac7r {
  stop-color: var(--svg-color--603c71, #603C71);
  stop-opacity: 0;
}

.q03-9xl3z {
  stop-color: var(--svg-color--7764b3, #7764B3);
}

.q92bisbnd {
  stop-color: var(--svg-color--6f3e55, #6F3E55);
}

.q9l62bb8x {
  d: path("M18.976 15.387v7.788a.96.96 0 0 1-.28.676l-.883.878a2.84 2.84 0 0 0-.834 2.018v.937c0 .174.14.316.316.316h1.366a.316.316 0 0 0 .316-.316v-.937c0-.227.09-.444.25-.604l3.874-3.88l.024-.009v-7.029z");
}

.qvruwibmg {
  stop-color: var(--svg-color--1f1818, #1F1818);
}

.r7nt8bqar {
  stop-color: var(--svg-color--855f53, #855F53);
}

.r8bvzmz9u {
  stop-color: var(--svg-color--d7aa87, #D7AA87);
  stop-opacity: 0;
}

.ro6jv7b4p {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m9.563 19.889l-.996 1.115a1.5 1.5 0 0 0 .073 2.075l1.538 1.495a1 1 0 0 0 .697.284h.625");
}

.rrlqfnbcn {
  d: path("M15.136 4.543c.304 0 .558.254.558.558a.563.563 0 0 1-.559.558z");
}

.s_8bwbbxs {
  stop-color: var(--svg-color--d6c8e5, #D6C8E5);
}

.s2jmff1mi {
  stop-color: var(--svg-color--a47c71, #A47C71);
}

.scfcuhb5w {
  stop-color: var(--svg-color--bb6a1e, #BB6A1E);
  stop-opacity: 0;
}

.sio64nb-w {
  d: path("M16.546 6.218h3.37v4.059H16.21c-.132 0-.253.09-.314.213l-.274.568c-.284.588-.893 1.035-1.543 1.035H11.41a.9.9 0 0 1-.893-.954a.93.93 0 0 1 .934-.862h2.578l1.694-3.552a.9.9 0 0 1 .822-.507");
}

.t5ng6m5ia {
  stop-color: var(--svg-color--9f7667, #9F7667);
}

.t7se8-bri {
  stop-color: var(--svg-color--5f3553, #5F3553);
  stop-opacity: 0;
}

.ttkfwetcv {
  stop-color: var(--svg-color--7668a3, #7668A3);
  stop-opacity: 0;
}

.tv37hulzl {
  d: path("M7.596 5.141c0 .083.068.15.15.15h1.09a.15.15 0 0 1 .15.15v2.922c0 .083.068.15.15.15h1.7a.15.15 0 0 1 .15.15v3.615c0 .083.067.15.15.15h2.475a4.01 4.01 0 0 0 4.006-4.012a.41.41 0 0 0-.412-.413H15.12c-.149 0-.216-.206-.107-.307a3.07 3.07 0 0 0 .985-2.258a.436.436 0 0 0-.435-.436H13.41c-.15 0-.223-.22-.123-.333a1.86 1.86 0 0 0 .473-1.242a.427.427 0 0 0-.426-.427H7.746a.15.15 0 0 0-.15.15z");
}

.u_g7lj_om {
  stop-color: var(--svg-color--f5f0fb, #F5F0FB);
}

.u6s_5wbvu {
  d: path("m15.937 5.923l.781 1.522l-1.562.812l-.782-1.553z");
}

.ufjhytbyb {
  stop-color: var(--svg-color--784d65, #784D65);
}

.ul8ntc5jf {
  stop-color: var(--svg-color--4a494a, #4A494A);
  stop-opacity: 0;
}

.uuu5cbc7v {
  fill: var(--svg-color--f1a72b, #F1A72B);
  d: path("M16.353 5.69s.751-.508.487-1.634c-.182-.01-.152.04-.314-.05c-.518-.275-1.045-.539-1.563-.802a1 1 0 0 1-.142.04c-.568.122-1.126.274-1.684.447c.192.091.466.142.832.142c1.156 0 1.156.7 1.156.7s.477-.122.477 1.309c0 .74.558.578.822.578c.437.01.508-.73-.07-.73");
}

.v_6b5hdqf {
  stop-color: var(--svg-color--46b988, #46B988);
  stop-opacity: 0;
}

.v-z8ul8_r {
  stop-color: var(--svg-color--343435, #343435);
  stop-opacity: 0;
}

.v0lxwrw8c {
  stop-color: var(--svg-color--2b292d, #2B292D);
}

.v3__gxa3g {
  d: path("M5.698 3c-1.01 0-1.847.75-1.984 1.725a.246.246 0 0 0 .241.283h1.507A2.006 2.006 0 0 0 7.467 3z");
}

.vjbpvrbhq {
  stop-color: var(--svg-color--7468a1, #7468A1);
}

.vk0ei6bvx {
  stop-color: var(--svg-color--3dc581, #3DC581);
}

.vsm9a27iv {
  stop-color: var(--svg-color--8b6c67, #8B6C67);
  stop-opacity: 0;
}

.vy6j7ybke {
  fill: var(--svg-color--524361, #524361);
  d: path("M21.762 8.165c0-1.248-1.015-1.477-2.253-1.477h-1.4v3.487l-.538.537c-.426.427-.66.995-.66 1.604v2.08h1.807l.66-1.884a.5.5 0 0 1 .131-.325L20.97 9.88a1.4 1.4 0 0 0 .244-.243c.345-.396.548-.903.548-1.472");
}

.w0qioubuo {
  stop-color: var(--svg-color--97716c, #97716C);
}

.wae82lo1m {
  fill: var(--svg-color--292929, #292929);
  d: path("M13.065 5.121a.3.3 0 0 1-.03-.121c0-.102.07-.193.152-.193s.152.081.152.193a.3.3 0 0 1-.03.121z");
}

.wb8annbpt {
  stop-color: var(--svg-color--6a433b, #6A433B);
  stop-opacity: 0;
}

.wi-b97b3f {
  stop-color: var(--svg-color--8b6c67, #8B6C67);
}

.wm54im16m {
  stop-color: var(--svg-color--643655, #643655);
  stop-opacity: 0;
}

.wo8d4bchi {
  d: path("M14.983 2.97h-.893c-.751 0-1.37.62-1.37 1.37v.386c0 .122-.03.243-.091.345c-.183.314-.264.335-.274.487c-.01.243.213.304.314.314c.03 0 .05.03.061.061c.02.853.183 1.451 1.197 1.451c.62 0 1.594-.314 1.878-1.035l.264-.984l.294-1.025a1.386 1.386 0 0 0-1.38-1.37");
}

.wqrxl6bcm {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.735 20.672c-.303.463-.725 1.64 0 2.64");
}

.x23z-v13r {
  fill: var(--svg-color--966d67, #966D67);
  d: path("M7.985 15.983L6.89 8.233l.844-.937c.145 1.156.725 4.575 1 6.875s.78 3.156 1.187 3.875l-.875.594c-.525-.725-.927-2.073-1.062-2.657");
}

.x8jpsgu1y {
  fill: var(--svg-color--f0c038, #F0C038);
  d: path("M12.234 10.277h-.823a.905.905 0 0 0-.903.903c0 .497.406.903.903.903h.823z");
}

.xvaoujpwx {
  d: path("M17.033 3.873a.252.252 0 0 1-.243.315h-4.333a.396.396 0 0 1 0-.792a.64.64 0 0 0 .517-.274a2.27 2.27 0 0 1 1.857-.964c1.066 0 1.959.731 2.202 1.715");
}

.y28nttbhx {
  stop-color: var(--svg-color--535254, #535254);
  stop-opacity: 0;
}

.y3ft0hbqe {
  stop-color: var(--svg-color--3da97e, #3DA97E);
  stop-opacity: 0;
}

.yywx__qpz {
  d: path("M11.375 13.969L6.891 2.453l2.474 2.53a3 3 0 0 1 .531.742l3.627 7.162z");
}

.zbcn3kg0t {
  stop-color: var(--svg-color--926c60, #926C60);
}

.zcrg57tqr {
  d: path("M17.985 26.622v.816h.38v-.82a1 1 0 0 1 .312-.726l2.917-2.767l-1.937-1.5v1.472a2 2 0 0 1-.42 1.225l-.833 1.075a2 2 0 0 0-.42 1.225");
}

.ziz970b6i {
  stop-color: var(--svg-color--633456, #633456);
  stop-opacity: 0;
}

.zk7_jm-pn {
  stop-color: var(--svg-color--784d65, #784D65);
  stop-opacity: 0;
}

.zn8a0d6yz {
  d: path("M15.217 4.188h-.589V7.09a.295.295 0 0 0 .589 0z");
}

.zp3ya6bcy {
  stop-color: var(--svg-color--6c4ba9, #6C4BA9);
  stop-opacity: 0;
}

.zq6nalbhy {
  stop-color: var(--svg-color--38b77c, #38B77C);
}

.zv6ipnb4d {
  stop-color: var(--svg-color--6544a7, #6544A7);
}

.zyl7mobjg {
  stop-color: var(--svg-color--d09e6c, #D09E6C);
}

</style>
