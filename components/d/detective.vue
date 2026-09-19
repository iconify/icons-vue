<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="i894f-b1z"/><path fill="url(#i2sRMqu)" class="dc5701bzu"/><path fill="url(#im4SsAb)" class="dc5701bzu"/><path fill="url(#i36e5Mb)" class="dc5701bzu"/><path fill="url(#iMBS5rc)" class="dc5701bzu"/><path fill="url(#iNuRt4c)" class="dc5701bzu"/><path class="sn-kgeb1h"/><path fill="url(#iPgDG1d)" class="yt_e8obhj"/><path fill="url(#ihqpYeb)" class="yt_e8obhj"/><path fill="url(#iuiO3gd)" class="yt_e8obhj"/><g filter="url(#iJCwwDe)"><path class="wjhbacmoh"/></g><path fill="url(#iPIbmle)" class="nusmn8mkb"/><path fill="url(#irCNyge)" class="nusmn8mkb"/><path fill="url(#i4raxIe)" class="nusmn8mkb"/><path fill="url(#iHFLA0d)" class="qxxw7qb-l"/><path fill="url(#iiusNOd)" class="qxxw7qb-l"/><g filter="url(#iExuUKd)"><path fill="url(#iMHFEkb)" class="dsu44zb8d"/></g><path fill="url(#iV7Tcle)" class="b7q0rbc2o"/><path fill="url(#i2u7SBe)" class="b7q0rbc2o"/><path fill="url(#ivqE6fb)" class="b7q0rbc2o"/><path fill="url(#iRnm9fc)" class="vm-5bgbzl"/><path fill="url(#ii3PcSr)" class="vm-5bgbzl"/><path fill="url(#ifsQOoU)" class="vm-5bgbzl"/><path fill="url(#iLpuKxd)" class="vm-5bgbzl"/><path fill="url(#i2oV4Wd)" class="vm-5bgbzl"/><path class="iaj--y3rg"/><path fill="url(#i2sVa8c)" class="zr3_bjbwz"/><path fill="url(#ifjdkUd)" class="zr3_bjbwz"/><path fill="url(#iq2o3Tb)" class="zr3_bjbwz"/><path fill="url(#ioxHHHc)" class="zr3_bjbwz"/><path fill="url(#iueOPUb)" class="zr3_bjbwz"/><path fill="url(#ix4U2Ae)" class="vpg6v_bwx"/><path fill="url(#iRFboge)" class="vpg6v_bwx"/><g filter="url(#iKGRPec)"><path fill="url(#il2M5Yr)" class="oy8g6abdr"/><path fill="url(#iZv7l2d)" class="oy8g6abdr"/><path fill="url(#iYSdtwd)" class="oy8g6abdr"/><path fill="url(#iYDIKxe)" class="oy8g6abdr"/><path fill="url(#iujs7cc)" class="oy8g6abdr"/></g><g filter="url(#irUbxze)"><path fill="url(#i6hDWEd)" class="a13xdtd-h"/><path fill="url(#iL4oKIe)" class="a13xdtd-h"/><path fill="url(#i3CfLkc)" class="a13xdtd-h"/><path fill="url(#i6mcsxe)" class="a13xdtd-h"/></g><path fill="url(#iyn7y6c)" class="t14p-tbmk"/><path fill="url(#iT1QhCr)" class="t14p-tbmk"/><path fill="url(#ix0gJoc)" class="m89uxybqp"/><path fill="url(#id2olTc)" class="m89uxybqp"/><g filter="url(#iDWDZCN)"><path fill="url(#iYxt1Td)" class="kuv4z3bnp"/></g><path fill="url(#ica62sz)" class="kuv4z3bnp"/><path fill="url(#iOwBmJc)" class="kuv4z3bnp"/><path fill="url(#i5759KR)" class="kuv4z3bnp"/><path fill="url(#iwbvSPd)" class="kuv4z3bnp"/><path fill="url(#iOtxPTb)" class="kuv4z3bnp"/><g filter="url(#ixXTkAb)"><path class="e3j1u3bbo"/></g><g filter="url(#irca9Nd)"><path class="wv8zolout"/><path fill="url(#iHjGGtc)" class="t-iv2yb_i"/><path fill="url(#iDSOP0q)" class="t-iv2yb_i"/><path fill="url(#iRTu4Rd)" class="t-iv2yb_i"/><path fill="url(#iQzbKoe)" class="t-iv2yb_i"/></g><g filter="url(#iTFABGc)"><path fill="url(#io0w4jd)" class="bi8-cvbdh"/></g><g filter="url(#ij4QEtb)"><path stroke="url(#i9tcLhb)" class="rkd37pb9t"/></g><path fill="url(#i0HnmxD)" class="c8qef-bmt"/><path class="xpl56pivl"/><path fill="url(#ihTTncj)" class="xbvt10bij"/><path class="v66duvtcd"/><g filter="url(#is9riid)"><path class="dtcjj3bli"/><path fill="url(#i8Vo77N)" class="kqxinlu1s"/></g><g filter="url(#iVk8Zwe)"><path fill="url(#ipNJzeb)" class="xwehoxbzc"/></g><path class="cj6se8w6d"/><path fill="url(#iO0LG2d)" class="p0tx705_o"/><path class="z_a87sb1t"/><g filter="url(#if0Q4Pe)"><path fill="url(#iod0Nxe)" class="nj3xrybjq"/></g><g filter="url(#iGtBjad)"><ellipse transform="rotate(-27.914 12.126 11.94)" class="r3du1qbjk"/><ellipse fill="url(#iwdEAcb)" transform="rotate(-27.914 12.126 11.94)" class="djzv1uz_y"/></g><path fill="url(#iLnSTje)" class="kyv0tab5x"/><path fill="url(#i6C5egd)" class="kyv0tab5x"/><path fill="url(#im61cmd)" class="kyv0tab5x"/><path fill="url(#iU5uMQb)" class="q6ombzbyl"/><path fill="url(#iZVBrld)" class="q6ombzbyl"/><g filter="url(#iUUiaVc)"><path class="y2xrk5b9p"/></g><g filter="url(#inW2Hge)"><path class="s4p6akbbx"/></g><g filter="url(#igzod3c)"><path fill="url(#iBmGFOY)" class="gakgbccfj"/></g><path fill="url(#iTXmTLd)" class="gakgbccfj"/><path fill="url(#iZbPprc)" class="gakgbccfj"/><g filter="url(#i0GjNld)"><path fill="url(#i2jNF6c)" class="ju71oo4bc"/></g><path fill="url(#iqZG1fg)" class="wlwgy8b3c"/><path fill="url(#iupqIVR)" class="wlwgy8b3c"/><path fill="url(#ipdm68c)" class="wlwgy8b3c"/><path fill="url(#ib95xge)" class="wlwgy8b3c"/><g filter="url(#idOWcMd)"><path fill="url(#ivQgERd)" class="g5ifrw1nu"/><path fill="url(#ilkEeZc)" class="g5ifrw1nu"/></g><rect fill="url(#isnf0Ea)" class="zbdu_7bzf"/><rect fill="url(#iGnFgwc)" class="zbdu_7bzf"/><rect fill="url(#iztyYVd)" class="zbdu_7bzf"/><rect fill="url(#icoAVGc)" class="zbdu_7bzf"/><g filter="url(#iLTa55c)"><circle class="w_ixtkbro"/></g><circle fill="url(#iYY8PXc)" class="pr4xqac-v"/><circle fill="url(#i8ZVBIb)" class="pr4xqac-v"/><g filter="url(#iNZtekd)"><path fill="url(#ifefeQT)" clip-rule="evenodd" class="zm0c3zbgy"/></g><rect fill="url(#is3S7Lb)" transform="rotate(-30 25.512 15.925)" class="wn75rnbwe"/><g filter="url(#iTu3Ite)"><path fill="url(#isk5Swe)" class="kkr9toi-a"/><path fill="url(#iabC3Pe)" class="kkr9toi-a"/><path fill="url(#i0qWope)" class="kkr9toi-a"/><path fill="url(#iaupsEc)" class="kkr9toi-a"/><path fill="url(#ipc9kFc)" class="kkr9toi-a"/></g><g filter="url(#iJVCVDd)"><path stroke="url(#ik1RnZb)" class="dlmfysgdv"/></g><g filter="url(#iE1C9vJ)"><path stroke="url(#i1BOxIe)" class="ucc3nmbyr"/></g><g filter="url(#iKdb3Xb)"><path stroke="url(#i98nGSa)" class="o3ktsvo5a"/></g><defs><radialGradient id="i2sRMqu" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.76)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="im4SsAb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.427 11.45)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="iMBS5rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.105)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="iNuRt4c" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.273 66.227)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="ihqpYeb" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .543 17.96)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iuiO3gd" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.833)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="iPIbmle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.87)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="irCNyge" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.529 12.672)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i4raxIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.87)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iHFLA0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.417)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="iiusNOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.87)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iMHFEkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.603)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iV7Tcle" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.73)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="iRnm9fc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.917)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="ifsQOoU" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.175 14.22)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iLpuKxd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.123 8.103)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="i2oV4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.05 20.811)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="i2sVa8c" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.417)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="iq2o3Tb" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.338 20.557)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ioxHHHc" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.524)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iueOPUb" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.701 20.81)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="ix4U2Ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.77344 -3.32031 0 14.875 19.823)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="b03y_pbel"/><stop offset="1" class="phm_r04pf"/></radialGradient><radialGradient id="iRFboge" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 .68753 -.20052 -1.22128 15.367 19.23)" gradientUnits="userSpaceOnUse"><stop class="efj5ccoqw"/><stop offset="1" class="k_2y5fb4u"/></radialGradient><radialGradient id="iYSdtwd" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.392 8.257)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="iujs7cc" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.23 21.227)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="i3CfLkc" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.198)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="i6mcsxe" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.398 12.957)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="iyn7y6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.96898 4.14136 -4.91961 -1.15108 21.014 14.11)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iT1QhCr" cx="0" cy="0" r="1" gradientTransform="matrix(.32582 .44684 -.3796 .2768 20.185 14.407)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ix0gJoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.48077 4.35816 -1.98099 .67308 8.689 14.24)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="id2olTc" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 1.1078 -.97177 .31031 9.424 14.23)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iYxt1Td" cx="0" cy="0" r="1" gradientTransform="matrix(-5.80709 0 0 -10.2727 17.97 13.063)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="ica62sz" cx="0" cy="0" r="1" gradientTransform="rotate(93.774 4.296 16.037)scale(6.79274 2.49729)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iOwBmJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57051 1.89081 0 12.528 11.752)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="i5759KR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70534 2.21188 0 17.616 11.295)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iwbvSPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.63106 -10.8149 0 14.904 12.543)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="uly7w_bmo"/><stop offset="1" class="yiqgv7bde"/></radialGradient><radialGradient id="iOtxPTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.32546 -6.41912 0 14.43 11.003)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="gj35r8buv"/><stop offset="1" class="urkvnpbdl"/></radialGradient><radialGradient id="iHjGGtc" cx="0" cy="0" r="1" gradientTransform="matrix(-.34314 -3.4375 1.29088 -.12886 15.648 14.48)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ldxgf3btd"/><stop offset="1" class="w4ju7-bed"/></radialGradient><radialGradient id="i9tcLhb" cx="0" cy="0" r="1" gradientTransform="matrix(.38563 -.68808 2.00234 1.1222 13.6 16.717)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i0HnmxD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.8006 3.22099 0 14.851 16.995)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ihTTncj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90121 -1.43348 0 17.275 12.046)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="te8mrib2c"/><stop offset="1" class="i2hdmc_po"/></radialGradient><radialGradient id="i8Vo77N" cx="0" cy="0" r="1" gradientTransform="matrix(-.25733 -.3316 .45655 -.35429 17.021 12.138)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iO0LG2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90126 -1.43355 0 12.428 12.046)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="te8mrib2c"/><stop offset="1" class="i2hdmc_po"/></radialGradient><radialGradient id="iwdEAcb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00858 -.54823 .659 -.01032 12.109 12.289)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6C5egd" cx="0" cy="0" r="1" gradientTransform="matrix(.6982 2.49182 -2.3774 .66613 19.98 12.061)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="im61cmd" cx="0" cy="0" r="1" gradientTransform="matrix(.87506 -1.20089 1.00658 .73348 20.38 12.666)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iZVBrld" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.523 9.82)scale(2.3512 2.31145)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iBmGFOY" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.042)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iTXmTLd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.074)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="iZbPprc" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.026)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iqZG1fg" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.583)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><radialGradient id="ivQgERd" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 7.13 19.713)scale(2.05934 1.65405)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="ilkEeZc" cx="0" cy="0" r="1" gradientTransform="matrix(.46055 -.45629 .48588 .4904 26.881 24.013)" gradientUnits="userSpaceOnUse"><stop class="xcc0mcchc"/><stop offset="1" class="lyxdnwxxe"/></radialGradient><radialGradient id="iztyYVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.175)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="icoAVGc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.214)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iYY8PXc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.198)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i8ZVBIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.678)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="is3S7Lb" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.067)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="iabC3Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57872 2.60975 -2.15908 -1.3061 27.845 23.968)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i0qWope" cx="0" cy="0" r="1" gradientTransform="matrix(2.52448 0 0 .50881 23.335 25.47)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iaupsEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.83004 0 0 .5704 23.132 26.92)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="ipc9kFc" cx="0" cy="0" r="1" gradientTransform="matrix(2.96797 0 0 .3582 23.028 28.302)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><linearGradient id="i36e5Mb" x1="6.988" x2="7.195" y1="29.355" y2="29.355" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iPgDG1d" x1="16.932" x2="14.847" y1="28.494" y2="28.068" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="i2u7SBe" x1="13.726" x2="14.226" y1="26.714" y2="26.761" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="ivqE6fb" x1="16.414" x2="15.153" y1="29.018" y2="29.071" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="ii3PcSr" x1="11.675" x2="12.612" y1="21.598" y2="21.417" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="ifjdkUd" x1="18.074" x2="17.138" y1="21.598" y2="21.417" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="il2M5Yr" x1="12.219" x2="9.392" y1="26.118" y2="26.755" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iZv7l2d" x1="9.392" x2="11.086" y1="16.925" y2="22.323" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="iYDIKxe" x1="12.268" x2="12.268" y1="29.87" y2="24.648" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="i6hDWEd" x1="18.023" x2="21.305" y1="29.073" y2="16.925" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iL4oKIe" x1="17" x2="17.152" y1="26.487" y2="26.519" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iDSOP0q" x1="13.66" x2="14.853" y1="13.811" y2="13.877" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iRTu4Rd" x1="14.851" x2="14.851" y1="14.427" y2="15.373" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iQzbKoe" x1="14.851" x2="14.851" y1="11.93" y2="12.396" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="io0w4jd" x1="14.851" x2="15.226" y1="11.792" y2="13.886" gradientUnits="userSpaceOnUse"><stop offset=".143" class="gmgp49kdt"/><stop offset="1" class="bsb2a9-gr"/></linearGradient><linearGradient id="ipNJzeb" x1="18.139" x2="17.79" y1="12.105" y2="12.32" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iod0Nxe" x1="13.253" x2="12.905" y1="12.105" y2="12.32" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLnSTje" x1="22.001" x2="20.66" y1="12.136" y2="14.553" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iU5uMQb" x1="8.353" x2="9.973" y1="12.918" y2="12.777" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="i2jNF6c" x1="23.304" x2="6.367" y1="9.386" y2="9.701" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iupqIVR" x1="8.554" x2="9.992" y1="6.825" y2="7.011" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="ipdm68c" x1="15.461" x2="15.461" y1="7.878" y2="7.675" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="ib95xge" x1="15.508" x2="15.508" y1="5.796" y2="5.933" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="isnf0Ea" x1="26.981" x2="24.992" y1="21.73" y2="21.73" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iGnFgwc" x1="26.336" x2="26.336" y1="25.417" y2="22.511" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="ifefeQT" x1="28.179" x2="23.367" y1="14.292" y2="19.73" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="isk5Swe" x1="28.259" x2="23.132" y1="27.755" y2="27.755" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".755" class="xwbtobibq"/></linearGradient><linearGradient id="ik1RnZb" x1="25.534" x2="23.53" y1="25.48" y2="25.48" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i1BOxIe" x1="25.449" x2="23.444" y1="26.904" y2="26.904" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i98nGSa" x1="25.534" x2="23.53" y1="28.328" y2="28.328" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><filter id="iJCwwDe" width="7.346" height="5.139" x="11.201" y="19.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".25"/></filter><filter id="iExuUKd" width="3.106" height="2.966" x="13.406" y="21.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="iKGRPec" width="8.299" height="13.046" x="5.293" y="16.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="irUbxze" width="8.299" height="13.046" x="16.154" y="16.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="iDWDZCN" width="11.853" height="13.909" x="9.227" y="6.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2747" result="effect2_innerShadow_4002_2747"/></filter><filter id="ixXTkAb" width="4.085" height="5.221" x="12.579" y="11.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".5"/></filter><filter id="irca9Nd" width="2.285" height="3.421" x="13.709" y="11.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="iTFABGc" width="2.285" height="3.421" x="13.709" y="11.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="ij4QEtb" width="4.075" height="1.692" x="12.814" y="15.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="is9riid" width=".851" height=".751" x="16.471" y="11.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="iVk8Zwe" width=".945" height=".97" x="17.415" y="11.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".1"/></filter><filter id="if0Q4Pe" width="1.051" height="1.11" x="12.48" y="11.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".1"/></filter><filter id="iGtBjad" width=".991" height=".76" x="11.63" y="11.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="iUUiaVc" width="1.421" height="2.588" x="8.177" y="11.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".125"/></filter><filter id="inW2Hge" width="1.551" height="2.614" x="20.113" y="11.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".125"/></filter><filter id="igzod3c" width="12.369" height="3.947" x="8.798" y="2.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="i0GjNld" width="19.912" height="4.003" x="4.916" y="7.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2747" result="effect2_innerShadow_4002_2747"/></filter><filter id="idOWcMd" width="2.761" height="3.973" x="26.147" y="21.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="iLTa55c" width="6.656" height="6.656" x="22.367" y="13.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".125"/></filter><filter id="iNZtekd" width="7.206" height="7.206" x="22.067" y="13.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="iTu3Ite" width="5.427" height="6.052" x="23.132" y="23.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2747"/></filter><filter id="iJVCVDd" width="2.212" height=".25" x="23.574" y="25.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="iE1C9vJ" width="2.212" height=".25" x="23.489" y="26.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter><filter id="iKdb3Xb" width="2.212" height=".25" x="23.574" y="28.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2747" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:detective" /></template>
<style>
.a13xdtd-h {
  d: path("M18.996 16.925L16.254 29.87h1.796c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.22-.906.141-1.031c-.078-.125-.375-.36-.672-.47c-.237-.087-.328-.202-.344-.25c-.057-.067-.068-.3.344-.687c.413-.387 1.308-1.067 1.703-1.36c.235-.187.652-.608.602-.983s-.651-.435-.766-.43z");
}

.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.b03y_pbel {
  stop-color: var(--svg-color--d17c26, #D17C26);
}

.b7q0rbc2o {
  d: path("m13.289 29.87l.854-5.407a.1.1 0 0 1 .098-.085h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bi8-cvbdh {
  d: path("m14.427 12.132l-.59 2.042c-.121.42.168.84.578.84h.873c.41 0 .699-.427.578-.84l-.59-2.042c-.127-.453-.717-.453-.85 0");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bsb2a9-gr {
  stop-color: var(--svg-color--e1862a, #E1862A);
  stop-opacity: 0;
}

.bslse1b3i {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
}

.bt46k-bry {
  stop-color: var(--svg-color--810937, #810937);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.c8qef-bmt {
  d: path("M14.851 16.28a3.34 3.34 0 0 1-1.539-.364c-.152-.077-.315.094-.22.232c.372.564 1.02.94 1.76.94c.738 0 1.386-.376 1.758-.94c.096-.144-.068-.31-.22-.232a3.3 3.3 0 0 1-1.539.365");
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cj6se8w6d {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.196 11.214c-.726 0-1.339.5-1.506 1.176c-.05.194.1.379.298.379h2.478a.256.256 0 0 0 .253-.302a1.556 1.556 0 0 0-1.524-1.253");
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.dc5701bzu {
  d: path("M2.727 29.87H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.502 2.727 29.871");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.djzv1uz_y {
  cx: 12.126px;
  cy: 11.939px;
  rx: 0.432px;
  ry: 0.219px;
}

.dlmfysgdv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.7 25.48h1.96");
}

.dsu44zb8d {
  d: path("m14.098 24.297l-.692-1.333l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.083h-1.284a.15.15 0 0 1-.134-.08");
}

.dtcjj3bli {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.204 11.726c.07.094-.077.21-.245.335s-.292.213-.363.119c-.07-.095.009-.273.176-.398c.168-.125.361-.15.432-.056");
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e3j1u3bbo {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.311 12.487l-.705 2.042c-.12.42.169.84.578.84h.874c.41 0 .699-.426.578-.84l-.59-2.042c-.127-.452-.602-.452-.735 0");
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.efj5ccoqw {
  stop-color: var(--svg-color--ad792e, #AD792E);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fk1gregde {
  stop-color: var(--svg-color--57497f, #57497F);
  stop-opacity: 0;
}

.foejprbbc {
  stop-color: var(--svg-color--767290, #767290);
}

.fpxhxfble {
  stop-color: var(--svg-color--5c4b6c, #5C4B6C);
}

.ft5dv1b6b {
  fill: none;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5ifrw1nu {
  d: path("M27.203 22.277c.58 0 1.056.475 1.056 1.055v2.418h-2.112v-2.418c.01-.58.475-1.055 1.056-1.055");
}

.gakgbccfj {
  d: path("M8.804 5.691a.1.1 0 0 0 .094.133h11.92a.1.1 0 0 0 .094-.133a87 87 0 0 0-.639-1.79c-.468-1.25-1.636-1.874-2.297-1.874c-.735-.017-1.259.317-1.65.567l-.193.12c-.578.344-.809.399-1.278.399c-.37 0-.761-.149-1.183-.368a5 5 0 0 1-.248-.141c-.436-.26-1.078-.643-1.905-.526c-.956.134-1.66.93-2.097 1.945c-.158.366-.386.997-.618 1.668");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gj35r8buv {
  stop-color: var(--svg-color--dc7c28, #DC7C28);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gmgp49kdt {
  stop-color: var(--svg-color--e1862a, #E1862A);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gtmq6ja1j {
  stop-color: var(--svg-color--ffd235, #FFD235);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.gzbsswvik {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
}

.i2hdmc_po {
  stop-color: var(--svg-color--63342e, #63342E);
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.i894f-b1z {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.87H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.502 2.727 29.871");
}

.iaj--y3rg {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.695l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.328.214.477.07c.15-.143.35-.484.467-.995");
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.ju71oo4bc {
  d: path("M6.386 7.827c-.26-.015-.991.035-1.316.36c-.357.357-.055 1.073.508 1.652c.539.555 2.335 1.739 5.18 1.739h8.167c2.874 0 4.689-1.184 5.234-1.739c.568-.579.874-1.295.513-1.652c-.328-.325-1.067-.375-1.33-.36z");
}

.k_2y5fb4u {
  stop-color: var(--svg-color--ad792e, #AD792E);
  stop-opacity: 0;
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kkr9toi-a {
  d: path("M23.132 24.767c0-.438.355-.799.793-.799h3.023c.724 0 1.31.587 1.31 1.31v3.5a1.09 1.09 0 0 1-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.434a.8.8 0 0 1-.444-.718");
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kqxinlu1s {
  d: path("M17.204 11.726c.07.094-.077.21-.245.335s-.292.213-.363.119c-.07-.095.009-.273.176-.398c.168-.125.361-.15.432-.056");
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kuv4z3bnp {
  d: path("M9.492 16.135a4.35 4.35 0 0 0 4.316 3.783h2.096a4.35 4.35 0 0 0 4.316-3.783c.131-2.093.263-4.177.36-6.268a1.61 1.61 0 0 0-1.532-1.59h-1.555a2.69 2.69 0 0 1-2.457-1.604a.74.74 0 0 0-.683-.464h-1.414c-2.05 0-3.712 1.68-3.712 3.753c0 2.067.13 4.1.265 6.173");
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.kyv0tab5x {
  d: path("M20.319 14.553q.111-1.773.204-3.545a1.788 1.788 0 0 1-.204 3.545");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.ldxgf3btd {
  stop-color: var(--svg-color--ffbb3a, #FFBB3A);
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lyxdnwxxe {
  stop-color: var(--svg-color--efa20d, #EFA20D);
  stop-opacity: 0;
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.m89uxybqp {
  d: path("M9.451 14.452a1.8 1.8 0 0 1-1.004-.343v1.034c0 .992.59 1.876 1.489 2.243a4.5 4.5 0 0 1-.384-1.31z");
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nj3xrybjq {
  d: path("M13.33 12.39c0-.32-.26-.533-.33-.598l-.32.31l.197.4z");
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nusmn8mkb {
  d: path("M7.023 29.87H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o3ktsvo5a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.7 28.328h1.96");
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.oy8g6abdr {
  d: path("m10.75 16.925l2.742 12.945h-1.797a1559 1559 0 0 1-4.625-7.734c-.422-.735-.219-.906-.14-1.031s.375-.36.671-.47c.238-.087.329-.202.344-.25c.057-.067.069-.3-.344-.687c-.412-.387-1.307-1.067-1.703-1.36c-.234-.187-.651-.608-.601-.983s.65-.435.765-.43z");
}

.p0tx705_o {
  d: path("M12.425 11.516a.99.99 0 0 0-.955 1.253h1.915q.035-.128.036-.262a1 1 0 0 0-.996-.991");
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.phm_r04pf {
  stop-color: var(--svg-color--db912b, #DB912B);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr4xqac-v {
  cx: 25.695px;
  cy: 17.042px;
  r: 2.984px;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q6ombzbyl {
  d: path("M9.237 11a1.788 1.788 0 0 0 .154 3.554a87 87 0 0 1-.154-3.555");
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qxxw7qb-l {
  d: path("M22.727 29.87h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r3du1qbjk {
  cx: 12.126px;
  cy: 11.939px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.432px;
  ry: 0.219px;
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rkd37pb9t {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.347 15.85a.245.245 0 0 0-.292.05a.23.23 0 0 0-.025.29a2.18 2.18 0 0 0 1.821.973c.765 0 1.436-.39 1.821-.973a.23.23 0 0 0-.025-.293a.245.245 0 0 0-.29-.048h-.002a3.25 3.25 0 0 1-1.504.357c-.552 0-1.07-.13-1.504-.357Z");
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.s4p6akbbx {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.363 13.83q.064-1.058.123-2.114a1.061 1.061 0 0 1-.123 2.114");
}

.sn-kgeb1h {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.87l-2.328-10.956l3.422-1.2l4.437 1.294l-2.28 10.862z");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t-iv2yb_i {
  d: path("m14.427 12.27l-.59 2.042c-.121.42.168.84.578.84h.873c.41 0 .699-.427.578-.84l-.59-2.042c-.127-.453-.717-.453-.85 0");
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t14p-tbmk {
  d: path("M20.251 14.452a1.8 1.8 0 0 0 1.005-.343v1.034c0 .992-.591 1.876-1.49 2.243q.286-.606.385-1.31z");
}

.te8mrib2c {
  stop-color: var(--svg-color--7d4443, #7D4443);
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
}

.tnc_xbdtt {
  stop-color: var(--svg-color--202d61, #202D61);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ucc3nmbyr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.614 26.904h1.962");
}

.uly7w_bmo {
  stop-color: var(--svg-color--ed9339, #ED9339);
  stop-opacity: 0;
}

.urkvnpbdl {
  stop-color: var(--svg-color--dc7c28, #DC7C28);
  stop-opacity: 0;
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.v66duvtcd {
  fill: var(--svg-color--000, #000);
  d: path("M16.71 12.508c0-.316.252-.568.567-.568a.565.565 0 0 1 .505.829h-1.005a.5.5 0 0 1-.067-.261");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vm-5bgbzl {
  d: path("m11.972 22.675l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.781c-.097.084-.327.214-.477.07c-.15-.143-.357-.503-.475-1.015");
}

.vpg6v_bwx {
  d: path("M12.625 19.495c.026.292.262.988.999 1.438c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.252-.664c.736-.45.973-1.146.999-1.438z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.w_ixtkbro {
  cx: 25.695px;
  cy: 17.042px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.w4ju7-bed {
  stop-color: var(--svg-color--ffbb3a, #FFBB3A);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wjhbacmoh {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.702 19.616l.69 3.215c.1.438.277.746.406.869c.128.123.325.011.407-.06l1.67-1.517l1.67 1.517c.081.071.278.183.407.06s.299-.415.4-.852l.696-3.232h-1.584l-1.59 2.116l-1.588-2.116z");
}

.wlwgy8b3c {
  d: path("M8.126 7.696a.1.1 0 0 0 .095.131h13.287a.1.1 0 0 0 .095-.132l-.193-.56l-.429-1.244a.1.1 0 0 0-.094-.068H8.829a.1.1 0 0 0-.094.068c-.19.554-.38 1.12-.532 1.575z");
}

.wn75rnbwe {
  width: 1.769px;
  height: 2.205px;
  x: 25.512px;
  y: 15.925px;
  rx: 0.885px;
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.wv8zolout {
  fill: var(--svg-color--ee981c, #EE981C);
  d: path("m14.427 12.27l-.59 2.042c-.121.42.168.84.578.84h.873c.41 0 .699-.427.578-.84l-.59-2.042c-.127-.453-.717-.453-.85 0");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xbvt10bij {
  d: path("M17.277 11.516a.99.99 0 0 1 .956 1.253h-1.916a.995.995 0 0 1 .96-1.253");
}

.xcc0mcchc {
  stop-color: var(--svg-color--efa20d, #EFA20D);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xpl56pivl {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.507 11.214c.726 0 1.339.5 1.505 1.176a.304.304 0 0 1-.297.379h-2.478a.256.256 0 0 1-.253-.302a1.55 1.55 0 0 1 1.523-1.253");
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.xwehoxbzc {
  d: path("M18.16 12.376a.93.93 0 0 0-.257-.513l-.288.316l.13.253z");
}

.y2xrk5b9p {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M9.255 11.733a1.062 1.062 0 0 0 .093 2.087a87 87 0 0 1-.093-2.087");
}

.yiqgv7bde {
  stop-color: var(--svg-color--c27032, #C27032);
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yt_e8obhj {
  d: path("m13.445 29.87l-2.328-10.956l3.422-1.2l4.437 1.294l-2.28 10.862z");
}

.z_a87sb1t {
  fill: var(--svg-color--000, #000);
  d: path("M12.993 12.507a.565.565 0 0 0-.568-.568a.565.565 0 0 0-.505.83h1.005a.56.56 0 0 0 .068-.262");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zbdu_7bzf {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.175px;
  rx: 1.286px;
}

.zm0c3zbgy {
  fill-rule: evenodd;
  d: path("M25.695 20.62a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.593a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.969");
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zr3_bjbwz {
  d: path("m17.77 22.695l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.328.214.477.07c.15-.143.35-.484.467-.995");
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
