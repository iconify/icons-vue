<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iXpgDGe)" class="hpvcutbck"/><path fill="url(#iJ7cClb)" class="ly3ts9b4s"/><path fill="url(#iCNYlqe)" class="ly3ts9b4s"/><g filter="url(#iixk1Gc)"><path fill="url(#izkMAae)" class="o3k84d6qx"/><path fill="url(#idzWqkZ)" class="o3k84d6qx"/></g><path class="izts3ubpq"/><path fill="url(#iLq3MMc)" class="sps5pcbwr"/><path fill="url(#ic7pgTd)" class="xt4lzl4ue"/><path fill="url(#iaRtErI)" class="xt4lzl4ue"/><path fill="url(#idlmQre)" class="recklxb7g"/><path fill="url(#i7FRp4l)" class="recklxb7g"/><g filter="url(#iIRBR4l)"><path fill="url(#iUQdKMc)" class="q1d-v_bcp"/><path fill="url(#im7Kkld)" class="q1d-v_bcp"/><path fill="url(#igSnNPd)" class="q1d-v_bcp"/></g><path fill="url(#iunBEkb)" class="q1d-v_bcp"/><path fill="url(#itDyKsC)" class="q1d-v_bcp"/><path fill="url(#iDUpjCc)" class="uv4xk__0j"/><path fill="url(#iIBT6Cb)" class="p6raiegyv"/><path fill="url(#iMI539b)" class="p6raiegyv"/><path fill="url(#iZhX5gd)" class="mftxj6bun"/><path fill="url(#i2AMQae)" class="rya-5gbax"/><path fill="url(#i8grkZc)" class="rya-5gbax"/><path fill="url(#igTd6ee)" class="q-_ztcbrq"/><g filter="url(#isTPYYb)"><path class="x53479-ni"/></g><g filter="url(#iR1HODb)"><path fill="url(#iSnyF6n)" class="y41itbdoc"/><path fill="url(#i5V4b7c)" class="y41itbdoc"/></g><g filter="url(#iPYWhQc)"><path class="btm36_but"/><path fill="url(#iNvpOCd)" class="m9g91_b8w"/><path fill="url(#ihj4QBc)" class="m9g91_b8w"/></g><path fill="url(#i5lJI6d)" class="lb4n_qbpt"/><path fill="url(#i1U45oe)" class="lb4n_qbpt"/><path fill="url(#iq0tkAd)" class="lb4n_qbpt"/><path fill="url(#igHW7hb)" class="lb4n_qbpt"/><path fill="url(#iOOX4Yc)" class="lb4n_qbpt"/><g filter="url(#ix49gkd)"><path class="ydlikx5zs"/></g><g filter="url(#ijB2WWc)"><path fill="url(#iKb7pmd)" class="g8_vizh5q"/></g><g filter="url(#iutcNyq)"><path fill="url(#iRJifme)" class="idaddmbps"/></g><path fill="url(#i8Hp9sd)" class="idaddmbps"/><path fill="url(#ixOH3zy)" class="idaddmbps"/><path fill="url(#iI5GfDn)" class="idaddmbps"/><g filter="url(#iihdjxc)"><path class="jy6i7_bqt"/></g><g filter="url(#iMWko7d)"><path class="jyudvn_ya"/><path fill="url(#iJNqcHb)" class="s0do32b4y"/><path fill="url(#izmY6Nc)" class="s0do32b4y"/><path fill="url(#iSVtf8d)" class="s0do32b4y"/></g><path fill="url(#igGbsLd)" class="s0do32b4y"/><g filter="url(#iuLZhLd)"><path stroke="url(#inwtklb)" class="d020v8bvh"/></g><path class="j5kw6msaz"/><g filter="url(#iBQ18ke)"><path class="uu5go2b4l"/></g><g filter="url(#ififVae)"><path class="st677ubxd"/></g><g filter="url(#iu6qwie)"><path class="ceqkr9bqv"/></g><g filter="url(#ioyzJxd)"><path class="p4vuboupa"/></g><g filter="url(#iFwpULb)"><path fill="url(#iCUwAtO)" class="nmsj-qb2m"/></g><path fill="url(#iPyK8Ib)" class="tcgz6g8ry"/><path fill="url(#iaGASiL)" class="tcgz6g8ry"/><path fill="url(#iwlddIc)" class="tcgz6g8ry"/><path fill="url(#iCTa6Le)" class="cgir1-bjx"/><path fill="url(#inQW2Zc)" class="cgir1-bjx"/><path fill="url(#iJ0o66d)" class="so7ho0b7c"/><path fill="url(#iylIxPb)" class="so7ho0b7c"/><path fill="url(#iNlIpxd)" class="so7ho0b7c"/><g filter="url(#ivaFmEb)"><path class="zldtt0buo"/></g><path class="t7malt78q"/><path fill="url(#iHBS3pc)" class="r8qsurb3u"/><path class="wi3gkdc5d"/><g filter="url(#iIl4fQd)"><path class="j8e_bxbeq"/><path fill="url(#ivH4YKb)" class="r9a7p34yh"/></g><g filter="url(#i7xtulb)"><path fill="url(#ixz0DQd)" class="dpsej6bgv"/></g><path class="sdwowt6hz"/><path fill="url(#iBQNHyb)" class="ynmig3fjf"/><path class="c86l7cbjk"/><g filter="url(#ihDrn9b)"><path fill="url(#idGPzkc)" class="d2rle138c"/></g><g filter="url(#ivQpkac)"><ellipse transform="rotate(-27.914 12.722 9.853)" class="lf3qebc6e"/><ellipse fill="url(#iFP3nGd)" transform="rotate(-27.914 12.722 9.853)" class="qsjqy-b8h"/></g><g filter="url(#i0FkQPc)"><path fill="url(#iqifode)" class="xkykp1f4a"/><path fill="url(#ijpG4uc)" class="xkykp1f4a"/></g><g filter="url(#i3OQEOe)"><path stroke="url(#into6EG)" class="n-iumhm_v"/></g><g filter="url(#i1U9IYd)"><path stroke="url(#ig4fQze)" class="a-3oa7b_e"/></g><g filter="url(#iSylk8l)"><path stroke="url(#iARPycB)" class="wl3az0c9v"/></g><defs><radialGradient id="iXpgDGe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.03 3.94)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iJ7cClb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 18.904 5.102)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="idzWqkZ" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.21 4.156)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="iLq3MMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.14 16.265)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iaRtErI" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 2.998 25.227)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="i7FRp4l" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.17 24.69)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iUQdKMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 15.21 16.133)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="igSnNPd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 14.356 19.531)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="itDyKsC" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 14.604 15.95)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iDUpjCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.13 19.632)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iIBT6Cb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.43272 -4.29817 0 15.819 16.555)" gradientUnits="userSpaceOnUse"><stop class="vooh3tegw"/><stop offset="1" class="xlyybr0fb"/></radialGradient><radialGradient id="iMI539b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.38565 -2.76771 0 15.14 15.31)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="bnge9kbad"/><stop offset="1" class="aum_h2loy"/></radialGradient><radialGradient id="iZhX5gd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 3 -1.50019 -.56257 20.826 12.07)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="l8h7nbbzi"/><stop offset=".805" class="e7uyszbuj"/></radialGradient><radialGradient id="i2AMQae" cx="0" cy="0" r="1" gradientTransform="matrix(.10939 2.375 -1.29772 .05977 10.357 12.305)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="fi9x9rb-a"/><stop offset="1" class="mlcqdhbsf"/></radialGradient><radialGradient id="igTd6ee" cx="0" cy="0" r="1" gradientTransform="matrix(1.75543 0 0 3.07202 8.57 10.57)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="i5V4b7c" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 26.03 -26.188)scale(1.02298 1.1676)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iNvpOCd" cx="0" cy="0" r="1" gradientTransform="matrix(.96029 -1.76625 1.03379 .56206 19.982 11.53)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ihj4QBc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.837 29.64)scale(.42659 .54994)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i1U45oe" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.139 11.684)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iOOX4Yc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.15 18.79)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iRJifme" cx="0" cy="0" r="1" gradientTransform="rotate(168.69 8.857 6.052)scale(6.19712 10.4454)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="i8Hp9sd" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.51 -1.753)scale(1.40625)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="f4d_slbvt"/><stop offset="1" class="mjltbqb6d"/></radialGradient><radialGradient id="ixOH3zy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34047 1.49191 0 17.685 9.587)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="iI5GfDn" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.891 -11.1693 0 15.208 8.292)" gradientUnits="userSpaceOnUse"><stop offset=".582" class="ba9c-9ben"/><stop offset="1" class="y_r2qxwfl"/></radialGradient><radialGradient id="inwtklb" cx="0" cy="0" r="1" gradientTransform="matrix(.28922 -.7681 1.9316 .72733 14.189 14.28)" gradientUnits="userSpaceOnUse"><stop class="f71zwr8du"/><stop offset="1" class="yxjq9v5jp"/></radialGradient><radialGradient id="iCUwAtO" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 0 0 .92188 17.857 7.055)" gradientUnits="userSpaceOnUse"><stop class="tm0e74wbn"/><stop offset="1" class="e59zk-ydg"/></radialGradient><radialGradient id="iPyK8Ib" cx="0" cy="0" r="1" gradientTransform="rotate(137.811 8.933 17.021)scale(1.65559 1.3064)" gradientUnits="userSpaceOnUse"><stop class="rht-9g91b"/><stop offset="1" class="fk-65dr-t"/></radialGradient><radialGradient id="iaGASiL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45313 1.43733 0 25.366 25.133)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="ap8mygb2m"/><stop offset="1" class="qayu9abrk"/></radialGradient><radialGradient id="iwlddIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79687 0 0 -3.09375 26.678 24.508)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="nb-_v43xz"/><stop offset=".922" class="ugwoxpb1x"/></radialGradient><radialGradient id="inQW2Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 25.324 24.75)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iJ0o66d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 25.347 21.57)" gradientUnits="userSpaceOnUse"><stop class="vwnwx2byo"/><stop offset="1" class="vzaknebes"/></radialGradient><radialGradient id="iylIxPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 24.85 21.953)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="gr2susb2n"/><stop offset="1" class="vnxqexb9a"/></radialGradient><radialGradient id="iHBS3pc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 17.424 9.95)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ivH4YKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.193 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBQNHyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 12.997 9.95)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iFP3nGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 12.706 10.172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijpG4uc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 26.983 24.554)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><filter id="iixk1Gc" width="20.537" height="10.328" x="4.692" y="4.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1798" result="effect2_innerShadow_4002_1798"/></filter><filter id="iIRBR4l" width="8" height="6.44" x="11.211" y="15.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="isTPYYb" width="3.24" height="3.24" x="8.621" y="8.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".25"/></filter><filter id="iR1HODb" width="3.59" height="3.59" x="18.361" y="8.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="iPYWhQc" width="3.327" height="3.327" x="18.367" y="8.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".25"/></filter><filter id="ix49gkd" width="8.45" height="4.612" x="10.941" y="25.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".125"/></filter><filter id="ijB2WWc" width="8.05" height="4.28" x="11.091" y="25.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="iutcNyq" width="10.869" height="10.18" x="10.023" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="iihdjxc" width="3.371" height="4.195" x="13.332" y="9.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".375"/></filter><filter id="iMWko7d" width="2.371" height="3.195" x="14.025" y="9.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".125"/></filter><filter id="iuLZhLd" width="3.833" height="1.572" x="13.234" y="13.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".05"/></filter><filter id="iBQ18ke" width="2.195" height="1.016" x="16.79" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.262745 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="ififVae" width="2.095" height=".766" x="16.84" y="7.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".075"/></filter><filter id="iu6qwie" width="2.195" height="1.016" x="11.43" y="7.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.262745 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="ioyzJxd" width="2.095" height=".766" x="11.48" y="7.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".075"/></filter><filter id="iFwpULb" width="4.103" height=".85" x="15.911" y="6.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.552941 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="ivaFmEb" width="7.625" height="9.853" x="21.064" y="10.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.490196 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.788235 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1798" result="effect2_innerShadow_4002_1798"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.552941 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1798" result="effect3_innerShadow_4002_1798"/></filter><filter id="iIl4fQd" width=".795" height=".703" x="16.681" y="9.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".05"/></filter><filter id="i7xtulb" width=".898" height=".921" x="17.535" y="9.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".1"/></filter><filter id="ihDrn9b" width=".995" height="1.05" x="13.027" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".1"/></filter><filter id="ivQpkac" width=".923" height=".712" x="12.26" y="9.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".05"/></filter><filter id="i0FkQPc" width="4.618" height="5.556" x="22.665" y="24.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1798"/></filter><filter id="i3OQEOe" width="2.047" height=".25" x="23.06" y="25.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".05"/></filter><filter id="i1U9IYd" width="2.047" height=".25" x="22.982" y="27.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".05"/></filter><filter id="iSylk8l" width="2.047" height=".25" x="23.06" y="28.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1798" stdDeviation=".05"/></filter><linearGradient id="iCNYlqe" x1="15.131" x2="15.131" y1="3.99" y2="4.043" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="izkMAae" x1="15.211" x2="15.211" y1="4.789" y2="14.821" gradientUnits="userSpaceOnUse"><stop class="ht4fz-b9x"/><stop offset="1" class="rk4knin1y"/></linearGradient><linearGradient id="ic7pgTd" x1="8.151" x2="4.56" y1="28.414" y2="28.414" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="idlmQre" x1="25.713" x2="22.171" y1="22.844" y2="29.15" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="im7Kkld" x1="19.211" x2="18.276" y1="18.477" y2="18.477" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iunBEkb" x1="11.211" x2="11.545" y1="18.477" y2="18.477" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="i8grkZc" x1="10.946" x2="10.217" y1="14.977" y2="13.852" gradientUnits="userSpaceOnUse"><stop class="q1ur86bmx"/><stop offset="1" class="x2cv0lbfc"/></linearGradient><linearGradient id="iSnyF6n" x1="21.117" x2="20.299" y1="9.478" y2="12.015" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i5lJI6d" x1="16.373" x2="15.161" y1="29.102" y2="21.977" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iq0tkAd" x1="22.224" x2="21.998" y1="29.633" y2="29.633" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="igHW7hb" x1="8.151" x2="8.275" y1="29.633" y2="29.633" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iKb7pmd" x1="12.998" x2="19.529" y1="28.321" y2="28.321" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="iJNqcHb" x1="14.349" x2="15.284" y1="11.63" y2="11.63" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="izmY6Nc" x1="16.146" x2="15.124" y1="11.954" y2="11.939" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iSVtf8d" x1="15.405" x2="15.405" y1="12.7" y2="12.124" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="igGbsLd" x1="15.336" x2="15.336" y1="12.742" y2="12.574" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iCTa6Le" x1="24.821" x2="24.821" y1="21.571" y2="24.75" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iNlIpxd" x1="24.849" x2="24.849" y1="22.274" y2="21.68" gradientUnits="userSpaceOnUse"><stop class="tun7z-ngg"/><stop offset="1" class="z3nh0_7nl"/></linearGradient><linearGradient id="ixz0DQd" x1="18.214" x2="17.895" y1="10.005" y2="10.201" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idGPzkc" x1="13.752" x2="13.433" y1="10.005" y2="10.201" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqifode" x1="26.693" x2="22.665" y1="28.023" y2="28.023" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="into6EG" x1="24.866" x2="23.03" y1="25.938" y2="25.938" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="ig4fQze" x1="24.788" x2="22.952" y1="27.242" y2="27.242" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient><linearGradient id="iARPycB" x1="24.866" x2="23.03" y1="28.547" y2="28.547" gradientUnits="userSpaceOnUse"><stop class="glaz8zb9m"/><stop offset="1" class="yidy664bk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:farmer" /></template>
<style>
.a-3oa7b_e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.107 27.242h1.797");
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.ap8mygb2m {
  stop-color: var(--svg-color--cf9826, #CF9826);
}

.aum_h2loy {
  stop-color: var(--svg-color--9a6904, #9A6904);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ba9c-9ben {
  stop-color: var(--svg-color--f99e3c, #F99E3C);
  stop-opacity: 0;
}

.bnge9kbad {
  stop-color: var(--svg-color--9a6904, #9A6904);
  stop-opacity: 0;
}

.btm36_but {
  fill: var(--svg-color--ffbf34, #FFBF34);
  d: path("M20.03 11.733a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.c86l7cbjk {
  fill: var(--svg-color--000, #000);
  d: path("M13.513 10.371a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.461.757h.918a.5.5 0 0 0 .061-.239");
}

.ceqkr9bqv {
  stroke: var(--svg-color--b44115, #B44115);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.68 8.258s.625-.473 1.696-.344");
}

.cgir1-bjx {
  d: path("M25.324 21.75h-1v3h1z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d020v8bvh {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.15 13.67c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36Z");
}

.d2rle138c {
  d: path("M13.822 10.265c0-.293-.238-.488-.302-.547l-.293.283l.18.367z");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dpsej6bgv {
  d: path("M18.233 10.252a.85.85 0 0 0-.235-.47l-.263.29l.119.232z");
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e59zk-ydg {
  stop-color: var(--svg-color--ffa62c, #FFA62C);
}

.e7uyszbuj {
  stop-color: var(--svg-color--d6922a, #D6922A);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f4d_slbvt {
  stop-color: var(--svg-color--f59732, #F59732);
}

.f71zwr8du {
  stop-color: var(--svg-color--ffb032, #FFB032);
}

.fi9x9rb-a {
  stop-color: var(--svg-color--ca7320, #CA7320);
}

.fk-65dr-t {
  stop-color: var(--svg-color--ffca2c, #FFCA2C);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g8_vizh5q {
  d: path("M18.63 25.79h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gr2susb2n {
  stop-color: var(--svg-color--947ca9, #947CA9);
  stop-opacity: 0;
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hpvcutbck {
  d: path("M21.13 5.89h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.ht4fz-b9x {
  stop-color: var(--svg-color--6a3d3e, #6A3D3E);
}

.idaddmbps {
  d: path("m20.38 8.94l.01-.11c.04-1.09-.83-2.04-1.93-2.04h-6.5c-1.14 0-2.03.97-1.93 2.1l.3 4.65a3.95 3.95 0 0 0 3.92 3.43h1.9c1.98 0 3.66-1.47 3.92-3.43z");
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.izts3ubpq {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.14 15.48c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j5kw6msaz {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M15.15 13.67c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.j8e_bxbeq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.36 9.657c.064.086-.07.192-.224.306c-.153.115-.267.196-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.jy6i7_bqt {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.638 10.515l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.jyudvn_ya {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("M14.83 10.29L14.3 12c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.l8h7nbbzi {
  stop-color: var(--svg-color--ffc034, #FFC034);
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lb4n_qbpt {
  d: path("M22.17 18.02c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.lf3qebc6e {
  cx: 12.722px;
  cy: 9.853px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.ly3ts9b4s {
  d: path("m9.31 5.53l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m9g91_b8w {
  d: path("M20.03 11.733a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mftxj6bun {
  d: path("M17.65 10.23v5.35l1.89-.65c.88-.3 1.46-1.13 1.46-2.06v-2.53c-1.12-.04-2.24-.08-3.35-.11");
}

.mjltbqb6d {
  stop-color: var(--svg-color--f59732, #F59732);
  stop-opacity: 0;
}

.mlcqdhbsf {
  stop-color: var(--svg-color--d2883b, #D2883B);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n-iumhm_v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.185 25.938h1.797");
}

.nb-_v43xz {
  stop-color: var(--svg-color--cd9d3e, #CD9D3E);
  stop-opacity: 0;
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nmsj-qb2m {
  d: path("M17.62 7.59h2.393c-.35-.48-.922-.8-1.552-.8h-2.55c.42.5 1.05.8 1.71.8");
}

.o3k84d6qx {
  d: path("M10.774 4.79c-.849.03-2.678.228-4.101 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.094 1.781 1.445 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.883-4.93V9.21c0-.969-.24-2.123-1.477-3.086c-1.424-1.107-3.253-1.304-4.102-1.336z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p4vuboupa {
  stroke: var(--svg-color--c76c5b, #C76C5B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.68 8.196s.625-.473 1.696-.344");
}

.p6raiegyv {
  d: path("M15.14 18.65c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.q-_ztcbrq {
  d: path("M10.24 12.24a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.q1d-v_bcp {
  d: path("m12.175 21.453l3.036-2.123l2.987 2.084c.42.325 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.594.823.964.563");
}

.q1ur86bmx {
  stop-color: var(--svg-color--b37641, #B37641);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qayu9abrk {
  stop-color: var(--svg-color--cf9826, #CF9826);
  stop-opacity: 0;
}

.qsjqy-b8h {
  cx: 12.722px;
  cy: 9.853px;
  rx: 0.395px;
  ry: 0.2px;
}

.qtwfj5bch {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r8qsurb3u {
  d: path("M17.427 9.466a.905.905 0 0 1 .872 1.144h-1.75a.91.91 0 0 1 .877-1.144");
}

.r9a7p34yh {
  d: path("M17.36 9.657c.064.086-.07.192-.224.306c-.153.115-.267.196-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.recklxb7g {
  d: path("M22.17 29.96V17.99h.007a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.rht-9g91b {
  stop-color: var(--svg-color--ffd740, #FFD740);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rk4knin1y {
  stop-color: var(--svg-color--6e4e4c, #6E4E4C);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.rya-5gbax {
  d: path("m9.28 10.17l-.01 2.69c0 .93.59 1.75 1.46 2.06l1.89.65v-5.43c-1.1 0-2.22 0-3.34.03");
}

.s0do32b4y {
  d: path("M14.83 10.29L14.3 12c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sdwowt6hz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.785 9.19c-.663 0-1.223.457-1.375 1.074a.278.278 0 0 0 .272.346h2.264a.233.233 0 0 0 .23-.276a1.42 1.42 0 0 0-1.391-1.144");
}

.so7ho0b7c {
  d: path("M24.087 19.969h1.524v1.734a.25.25 0 0 1-.25.25h-1.024a.25.25 0 0 1-.25-.25z");
}

.sps5pcbwr {
  d: path("M15.14 15.48c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.st677ubxd {
  stroke: var(--svg-color--c76c5b, #C76C5B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.735 8.196s-.625-.473-1.695-.344");
}

.t7malt78q {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.637 9.19c.662 0 1.222.457 1.374 1.074a.278.278 0 0 1-.271.346h-2.264a.234.234 0 0 1-.23-.276c.127-.65.7-1.144 1.39-1.144");
}

.tcgz6g8ry {
  d: path("M25.983 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.44-1 1-1");
}

.tm0e74wbn {
  stop-color: var(--svg-color--ffc032, #FFC032);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tun7z-ngg {
  stop-color: var(--svg-color--9e83be, #9E83BE);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ugwoxpb1x {
  stop-color: var(--svg-color--cd9d3e, #CD9D3E);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uu5go2b4l {
  stroke: var(--svg-color--b44115, #B44115);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.735 8.258s-.625-.473-1.695-.344");
}

.uv4xk__0j {
  d: path("m16.06 19.67l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vnxqexb9a {
  stop-color: var(--svg-color--947ca9, #947CA9);
}

.vooh3tegw {
  stop-color: var(--svg-color--cd8a31, #CD8A31);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.vwnwx2byo {
  stop-color: var(--svg-color--d2c4e1, #D2C4E1);
}

.vzaknebes {
  stop-color: var(--svg-color--b198c9, #B198C9);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wi3gkdc5d {
  fill: var(--svg-color--000, #000);
  d: path("M16.908 10.371c0-.288.23-.518.518-.518a.516.516 0 0 1 .462.757h-.918a.47.47 0 0 1-.062-.239");
}

.wl3az0c9v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.185 28.547h1.797");
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.x2cv0lbfc {
  stop-color: var(--svg-color--b37641, #B37641);
  stop-opacity: 0;
}

.x53479-ni {
  fill: var(--svg-color--da821c, #DA821C);
  d: path("M10.24 11.69a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xkykp1f4a {
  d: path("M22.665 25.286a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.xlyybr0fb {
  stop-color: var(--svg-color--c6912a, #C6912A);
}

.xt4lzl4ue {
  d: path("M8.15 29.96V17.99h-.006a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.y_r2qxwfl {
  stop-color: var(--svg-color--c38035, #C38035);
}

.y41itbdoc {
  d: path("M20.03 12.24a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.ydlikx5zs {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M18.63 25.79h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.yidy664bk {
  stop-color: var(--svg-color--c88714, #C88714);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.ynmig3fjf {
  d: path("M12.995 9.466a.906.906 0 0 0-.873 1.144h1.75a1 1 0 0 0 .032-.239a.91.91 0 0 0-.91-.905");
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yxjq9v5jp {
  stop-color: var(--svg-color--ffb032, #FFB032);
  stop-opacity: 0;
}

.z3nh0_7nl {
  stop-color: var(--svg-color--9e83be, #9E83BE);
  stop-opacity: 0;
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zldtt0buo {
  fill: var(--svg-color--c7b3db, #C7B3DB);
  d: path("M21.966 11.024a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.601.601 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.601");
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
