<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><g filter="url(#iV8mRrc)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#iQZRcuc)"><path class="ii_vcdblz"/></g><g filter="url(#ipkO7hc)"><path class="x9-b3hbfy"/></g><g filter="url(#iWbW7Fc)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iZLtlOc)" class="ndlc49hkf"/><path fill="url(#iHff3Oe)" class="ndlc49hkf"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOpcCOc)" class="u-q3e7b8s"/><path fill="url(#iHWrc1d)" class="mrp1fzb0j"/><path fill="url(#i3MqPDW)" class="fbjx3y-qb"/><path fill="url(#i8fe9wd)" class="fbjx3y-qb"/><g filter="url(#i3fSfBc)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iUEJUid)" class="ue1gv6enh"/><path fill="url(#i294t4w)" class="ue1gv6enh"/><g filter="url(#i7vRNDc)"><path fill="url(#igKMsTc)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#iQrUlPd)"><path fill="url(#iOKq7lc)" class="qtzewq2gr"/><path fill="url(#iI8fpid)" class="qtzewq2gr"/><path fill="url(#ivXSXbb)" class="qtzewq2gr"/><path fill="url(#inoTRvd)" class="qtzewq2gr"/><path fill="url(#ifrujYb)" class="qtzewq2gr"/></g><path fill="url(#iElbqJe)" class="qtzewq2gr"/><g filter="url(#i6lNJuc)"><path stroke="url(#ivhW0ze)" class="bzs2-ddka"/></g><g filter="url(#iXLpGfc)"><path stroke="url(#iNT2srd)" class="pjsi77bhr"/></g><g filter="url(#iSuVx6J)"><path stroke="url(#iflwwud)" class="oool1tdti"/></g><path fill="url(#iv3AA6b)" class="tagaeklzk"/><path fill="url(#i14xbxc)" class="gepvdybmy"/><path class="hcpsq0yfi"/><g filter="url(#ielYzYc)"><path fill="url(#iGNwSvb)" class="fytj70bfu"/></g><path fill="url(#iPxp4Zb)" class="j1t3bc_8m"/><path fill="url(#iEVuVzK)" class="j1t3bc_8m"/><path fill="url(#iy4OEFd)" class="j1t3bc_8m"/><path fill="url(#ix1t5uI)" class="j1t3bc_8m"/><path fill="url(#iWjOcDd)" class="j1t3bc_8m"/><path fill="url(#ifvXknP)" class="j1t3bc_8m"/><g filter="url(#iltht6b)"><path class="wb_ynyb7f"/></g><g filter="url(#iejLpCW)"><path class="wyyomf4yi"/><path fill="url(#iWHiVTc)" class="aiix5bd1l"/><path fill="url(#iXCZnGy)" class="aiix5bd1l"/><path fill="url(#iBzGjJd)" class="aiix5bd1l"/><path fill="url(#iurjjob)" class="aiix5bd1l"/><path fill="url(#i8ESVcb)" class="aiix5bd1l"/></g><g filter="url(#i8Rcdxe)"><path stroke="url(#i3zVl1d)" class="tadvv5bzp"/></g><path fill="url(#iyqeQ6W)" class="a--_rwbzu"/><g filter="url(#iyciihi)"><path class="m27k_nb6m"/></g><g filter="url(#iPeau4v)"><path class="cwk-2fbyy"/></g><path class="hbd74rbhc"/><path fill="url(#iJSBhrc)" class="i7-q4i4gv"/><path class="t6zrydbnh"/><g filter="url(#iwcfqne)"><path class="hm1urwb5k"/><path fill="url(#i7Dd5Gb)" class="dnhtcubjq"/></g><g filter="url(#ilnmLhe)"><path fill="url(#iOAeqAb)" class="gg9zsqq5x"/></g><path class="k0j70z43j"/><path fill="url(#i1p7mTd)" class="wqouu2b2u"/><path class="rvb3y3bkj"/><g filter="url(#irjXY1c)"><path fill="url(#iJfNMjd)" class="g_ac30bwp"/></g><g filter="url(#i6opRck)"><ellipse transform="rotate(-27.914 12.232 9.819)" class="e3vivxbiw"/><ellipse fill="url(#iV8gmXc)" transform="rotate(-27.914 12.232 9.819)" class="py0n-wnry"/></g><path fill="url(#iIjgfBb)" class="x1_659jhp"/><g filter="url(#i0SHTqg)"><path fill="url(#iWYe6Ae)" class="vm6kozbyx"/></g><g filter="url(#iV4Dkbd)"><path fill="url(#ikcfmeP)" class="wg0ef3bbj"/></g><g filter="url(#iLTREfd)"><path fill="url(#i3RQ7Xf)" class="fg1b9sbrt"/></g><g filter="url(#ilh8Yyi)"><path class="br-g3ebbx"/></g><g filter="url(#i8NeuQb)"><path class="vvma5rbrc"/></g><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#i2JfQ2b)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#iJvT0yb)"><path class="ojb-ttbmo"/></g><g filter="url(#iVaJsDd)"><path class="ac3zfwb5z"/></g><path fill="url(#iyIB07c)" class="juswexddr"/><defs><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOpcCOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ap92plmur"/><stop offset="1" class="c5np98r4l"/></radialGradient><radialGradient id="iHWrc1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.55575 -2.11246 0 14.734 16.875)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="o1gf6ebie"/><stop offset=".707" class="y13139flk"/><stop offset="1" class="g67_t8fua"/></radialGradient><radialGradient id="i3MqPDW" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 10.772 15.093)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="i8fe9wd" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.205 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="i294t4w" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="wp6rq3sqk"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="iI8fpid" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ivXSXbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="inoTRvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ifrujYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iElbqJe" cx="0" cy="0" r="1" gradientTransform="scale(3.72384 5.01752)rotate(90 1.09 6.07)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="iv3AA6b" cx="0" cy="0" r="1" gradientTransform="rotate(79.857 2.687 17.858)scale(1.73016 1.88552)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="usq0mac0v"/><stop offset="1" class="b-4q2-4nc"/></radialGradient><radialGradient id="iGNwSvb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33067 0 0 -9.4299 17.597 10.85)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iPxp4Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.7187 -10.5522 0 15.34 5.116)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="dkc_aibit"/><stop offset=".973" class="h6pwsobze"/></radialGradient><radialGradient id="iEVuVzK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28125 1.59375 0 17.043 9.71)" gradientUnits="userSpaceOnUse"><stop class="xuipl1bei"/><stop offset="1" class="f165ur9pt"/></radialGradient><radialGradient id="iy4OEFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40627 7.3125 -7.85018 -.43614 20.012 7.18)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="tpyby8h1l"/><stop offset="1" class="fo2kykbuh"/></radialGradient><radialGradient id="iWjOcDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 3.90625 -4.68927 1.46305 11.106 6.772)" gradientUnits="userSpaceOnUse"><stop class="ysugf1aqs"/><stop offset="1" class="lkgptrbsy"/></radialGradient><radialGradient id="ifvXknP" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.236 -1.589)scale(1.46875)" gradientUnits="userSpaceOnUse"><stop offset=".404" class="kg3uvq1fk"/><stop offset="1" class="n26l-i5_v"/></radialGradient><radialGradient id="iXCZnGy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2489 -.78227 0 15.21 12.364)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iurjjob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55106 .71115 -1.14287 -2.49268 15.328 11.783)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iyqeQ6W" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73491 2.95674 0 14.734 14.46)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iJSBhrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82728 -1.31588 0 16.959 9.917)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7Dd5Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23648 -.30473 .41955 -.32557 16.726 10.002)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1p7mTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82732 -1.31594 0 12.509 9.917)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iV8gmXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00789 -.5038 .60559 -.00948 12.217 10.14)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIjgfBb" cx="0" cy="0" r="1" gradientTransform="rotate(115.142 7.34 11.119)scale(3.48659 4.07533)" gradientUnits="userSpaceOnUse"><stop class="u_qgni50q"/><stop offset="1" class="wg0u_rd0m"/><stop offset="1" class="alkmbvb7w"/></radialGradient><radialGradient id="iWYe6Ae" cx="0" cy="0" r="1" gradientTransform="matrix(.875 3.25 -2.1887 .58927 9.043 9.206)" gradientUnits="userSpaceOnUse"><stop class="odxs-cbnv"/><stop offset="1" class="a02_cfb_b"/></radialGradient><radialGradient id="i3RQ7Xf" cx="0" cy="0" r="1" gradientTransform="matrix(.82031 -.20282 .21479 .8687 19.7 10.794)" gradientUnits="userSpaceOnUse"><stop class="z2op5sb3v"/><stop offset="1" class="ig-3c1b3u"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><radialGradient id="iyIB07c" cx="0" cy="0" r="1" gradientTransform="matrix(.76716 -1.1875 .58464 .3777 8.815 9.178)" gradientUnits="userSpaceOnUse"><stop class="c8c_uixdk"/><stop offset="1" class="efwd38hnk"/></radialGradient><filter id="iV8mRrc" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="iQZRcuc" width="5.492" height="8.119" x="9.76" y="14.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".5"/></filter><filter id="ipkO7hc" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".5"/></filter><filter id="iWbW7Fc" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="i3fSfBc" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="i7vRNDc" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="iQrUlPd" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="i6lNJuc" width="2.097" height=".3" x="22.598" y="25.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".05"/></filter><filter id="iXLpGfc" width="2.097" height=".3" x="22.52" y="27.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".05"/></filter><filter id="iSuVx6J" width="2.097" height=".3" x="22.598" y="28.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".05"/></filter><filter id="ielYzYc" width="11.421" height="12.784" x="9.571" y="4.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2032" result="effect2_innerShadow_4002_2032"/></filter><filter id="iltht6b" width="3.914" height="4.957" x="12.565" y="9.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".5"/></filter><filter id="iejLpCW" width="2.314" height="3.357" x="13.577" y="9.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".1"/></filter><filter id="i8Rcdxe" width="3.682" height="1.494" x="12.893" y="13.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".05"/></filter><filter id="iyciihi" width="2.383" height="1.21" x="16.354" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.0784314 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="iPeau4v" width="2.383" height="1.195" x="10.994" y="7.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.0784314 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="iwcfqne" width=".798" height=".706" x="16.212" y="9.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".05"/></filter><filter id="ilnmLhe" width=".901" height=".923" x="17.07" y="9.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".1"/></filter><filter id="irjXY1c" width=".998" height="1.053" x="12.54" y="9.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".1"/></filter><filter id="i6opRck" width=".927" height=".714" x="11.769" y="9.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".05"/></filter><filter id="i0SHTqg" width="1.651" height="3.263" x="8.171" y="8.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.639216 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="iV4Dkbd" width="1.345" height="2.416" x="8.526" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".125"/></filter><filter id="iLTREfd" width="1.465" height="2.441" x="19.621" y="9.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".125"/></filter><filter id="ilh8Yyi" width="2.088" height=".818" x="11.094" y="7.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".075"/></filter><filter id="i8NeuQb" width="2.065" height=".83" x="16.499" y="7.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2032" stdDeviation=".075"/></filter><filter id="i2JfQ2b" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2032" result="effect2_innerShadow_4002_2032"/></filter><filter id="iJvT0yb" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><filter id="iVaJsDd" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2032"/></filter><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iZLtlOc" x1="8.242" x2="21.651" y1="9.948" y2="9.948" gradientUnits="userSpaceOnUse"><stop offset=".006" class="z-f4zlb4n"/><stop offset="1" class="z88owpbip"/></linearGradient><linearGradient id="iHff3Oe" x1="17.985" x2="17.985" y1="10.031" y2="9.742" gradientUnits="userSpaceOnUse"><stop class="q9u3nxbxg"/><stop offset="1" class="lvlvw7bgp"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="iUEJUid" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop class="ec1jnjbjz"/><stop offset="1" class="yd41utmlw"/></linearGradient><linearGradient id="igKMsTc" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="avgmeibok"/><stop offset="1" class="lasn3qwok"/></linearGradient><linearGradient id="iOKq7lc" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="ivhW0ze" x1="22.748" x2="24.458" y1="26.08" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iNT2srd" x1="22.67" x2="24.38" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iflwwud" x1="22.748" x2="24.458" y1="28.689" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i14xbxc" x1="8.854" x2="9.676" y1="12.655" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="hh_sy8brk"/><stop offset="1" class="jcemnlupa"/></linearGradient><linearGradient id="ix1t5uI" x1="9.571" x2="10.918" y1="11.616" y2="11.491" gradientUnits="userSpaceOnUse"><stop offset=".305" class="p09lm7njz"/><stop offset="1" class="qvxq5kbmq"/></linearGradient><linearGradient id="iWHiVTc" x1="15.691" x2="14.734" y1="11.616" y2="11.7" gradientUnits="userSpaceOnUse"><stop class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iBzGjJd" x1="14.734" x2="14.734" y1="12.826" y2="12.352" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i8ESVcb" x1="14.734" x2="14.734" y1="9.937" y2="10.625" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="i3zVl1d" x1="13.508" x2="13.833" y1="14.302" y2="13.451" gradientUnits="userSpaceOnUse"><stop class="uhvh9szrw"/><stop offset="1" class="ges79ib3m"/></linearGradient><linearGradient id="iOAeqAb" x1="17.752" x2="17.432" y1="9.972" y2="10.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJfNMjd" x1="13.267" x2="12.947" y1="9.971" y2="10.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikcfmeP" x1="9.621" x2="8.84" y1="10.505" y2="10.528" gradientUnits="userSpaceOnUse"><stop class="tm3a41odp"/><stop offset="1" class="r8mrl8bdh"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:factory-worker-light" /></template>
<style>
.a--_rwbzu {
  d: path("M14.734 13.804a3.06 3.06 0 0 1-1.413-.335c-.14-.07-.29.087-.202.214a1.93 1.93 0 0 0 1.615.862a1.93 1.93 0 0 0 1.614-.862c.088-.132-.062-.284-.202-.213c-.409.213-.89.334-1.412.334");
}

.a02_cfb_b {
  stop-color: var(--svg-color--c8887e, #C8887E);
}

.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.aiix5bd1l {
  d: path("m14.344 10.248l-.542 1.875c-.11.385.155.77.53.77h.803c.376 0 .641-.39.53-.77l-.541-1.875c-.117-.415-.659-.415-.78 0");
}

.alkmbvb7w {
  stop-color: var(--svg-color--d5a89f, #D5A89F);
}

.ap92plmur {
  stop-color: var(--svg-color--655676, #655676);
  stop-opacity: 0;
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.avgmeibok {
  stop-color: var(--svg-color--73d7ff, #73D7FF);
}

.b-4q2-4nc {
  stop-color: var(--svg-color--2d1c2c, #2D1C2C);
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.br-g3ebbx {
  stroke: var(--svg-color--252325, #252325);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.294 8.249c.262-.188.915-.519 1.688-.389");
}

.bzs2-ddka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 26.002h1.797");
}

.c5np98r4l {
  stop-color: var(--svg-color--655676, #655676);
}

.c8c_uixdk {
  stop-color: var(--svg-color--3e2b28, #3E2B28);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cwk-2fbyy {
  fill: var(--svg-color--0d0b10, #0D0B10);
  d: path("M11.256 7.963a2.83 2.83 0 0 1 1.773-.366a.283.283 0 0 1-.069.561a2.26 2.26 0 0 0-1.414.29a1 1 0 0 0-.093.062l-.003.002a.283.283 0 0 1-.346-.447z");
}

.d7sh3eboe {
  stop-color: var(--svg-color--26386d, #26386D);
}

.dkc_aibit {
  stop-color: var(--svg-color--d49da0, #D49DA0);
  stop-opacity: 0;
}

.dnhtcubjq {
  d: path("M16.894 9.623c.065.086-.07.192-.225.307c-.154.116-.268.197-.333.11s.007-.25.161-.366s.332-.138.397-.051");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e3vivxbiw {
  cx: 12.232px;
  cy: 9.819px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.ec1jnjbjz {
  stop-color: var(--svg-color--675479, #675479);
}

.efwd38hnk {
  stop-color: var(--svg-color--2f142a, #2F142A);
}

.f165ur9pt {
  stop-color: var(--svg-color--dea69b, #DEA69B);
  stop-opacity: 0;
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fg1b9sbrt {
  d: path("M19.871 11.561q.06-.97.113-1.94a.974.974 0 0 1-.113 1.94");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fo2kykbuh {
  stop-color: var(--svg-color--daa39b, #DAA39B);
  stop-opacity: 0;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.fytj70bfu {
  d: path("M9.814 13.67a3.99 3.99 0 0 0 3.962 3.473H15.7c2.005 0 3.7-1.482 3.962-3.473c.12-1.92.241-3.834.33-5.753a1.48 1.48 0 0 0-1.406-1.46H17.16a2.47 2.47 0 0 1-2.256-1.472a.68.68 0 0 0-.627-.426h-1.298c-1.882 0-3.407 1.542-3.407 3.445c0 1.897.118 3.764.243 5.666");
}

.g_ac30bwp {
  d: path("M13.338 10.233c0-.294-.239-.49-.304-.55l-.294.285l.181.369z");
}

.g67_t8fua {
  stop-color: var(--svg-color--8d535a, #8D535A);
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.gepvdybmy {
  d: path("M9.777 12.125a1.67 1.67 0 0 1-.923-.315v.95c0 .91.543 1.722 1.368 2.059a4.2 4.2 0 0 1-.353-1.204z");
}

.ges79ib3m {
  stop-color: var(--svg-color--e3b2a8, #E3B2A8);
  stop-opacity: 0;
}

.gg9zsqq5x {
  d: path("M17.771 10.22a.86.86 0 0 0-.236-.471l-.265.29l.12.233z");
}

.h6pwsobze {
  stop-color: var(--svg-color--b67999, #B67999);
}

.hbd74rbhc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.172 9.153c.666 0 1.228.46 1.381 1.08a.28.28 0 0 1-.273.347h-2.275a.235.235 0 0 1-.231-.277a1.425 1.425 0 0 1 1.398-1.15");
}

.hcpsq0yfi {
  fill: var(--svg-color--0d0413, #0D0413);
  d: path("M19.94 7.598c.24.172.54.448.756.691v1.024c-.218-.168-.493-.19-.765-.257c.007-.317.01-.734.01-1.052c0-.096.008-.312 0-.406");
}

.hh_sy8brk {
  stop-color: var(--svg-color--483936, #483936);
}

.hm1urwb5k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.894 9.623c.065.086-.07.192-.225.307c-.154.116-.268.197-.333.11s.007-.25.161-.366s.332-.138.397-.051");
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.i7-q4i4gv {
  d: path("M16.96 9.43a.91.91 0 0 1 .878 1.15H16.08a.914.914 0 0 1 .881-1.15");
}

.ig-3c1b3u {
  stop-color: var(--svg-color--976763, #976763);
}

.ii_vcdblz {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M10.76 16.494v4.63c-.002.26.024.579.25.72c.234.144.581-.02.743-.142l2.5-1.765V15.78a11 11 0 0 0-3.492.713");
}

.it1_ig0bc {
  stop-color: var(--svg-color--57525e, #57525E);
}

.iv7bj_baj {
  stop-color: var(--svg-color--4680db, #4680DB);
  stop-opacity: 0;
}

.ixw-oi7aq {
  stop-color: var(--svg-color--3d3248, #3D3248);
}

.iycy_sbnz {
  d: path("M7.366 8.01h-.707a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.707c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.j0xtzac4y {
  stop-color: var(--svg-color--4d79b0, #4D79B0);
  stop-opacity: 0;
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j1t3bc_8m {
  d: path("M9.814 13.67a3.99 3.99 0 0 0 3.962 3.473H15.7c2.005 0 3.7-1.482 3.962-3.473c.12-1.92.26-4.217.35-6.136c-.01-.782-.647-1.045-1.426-1.078H17.16a2.47 2.47 0 0 1-2.256-1.47a.68.68 0 0 0-.627-.427h-1.298c-1.882 0-3.407 1.542-3.407 3.445c0 1.897.118 3.764.243 5.666");
}

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.javsik_yi {
  fill: var(--svg-color--f3d8ed, #F3D8ED);
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.jcemnlupa {
  stop-color: var(--svg-color--2b1e23, #2B1E23);
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.juswexddr {
  d: path("M9.582 7.718a7 7 0 0 0-.767.739v.82c.219-.168.48-.281.765-.321q-.01-.475-.01-.952q0-.144.012-.286");
}

.k0j70z43j {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.296 9.153c-.666 0-1.229.459-1.382 1.08a.28.28 0 0 0 .273.347h2.275a.235.235 0 0 0 .232-.277a1.43 1.43 0 0 0-1.398-1.15");
}

.kc9q3mbff {
  fill: var(--svg-color--c6c6c6, #C6C6C6);
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.kg3uvq1fk {
  stop-color: var(--svg-color--d1978d, #D1978D);
}

.ky_dg6bhp {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.lasn3qwok {
  stop-color: var(--svg-color--93ffff, #93FFFF);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkgptrbsy {
  stop-color: var(--svg-color--b97985, #B97985);
  stop-opacity: 0;
}

.lo1ogpbbw {
  stop-color: var(--svg-color--391f48, #391F48);
  stop-opacity: 0;
}

.lt_b3wboz {
  d: path("m3.769 30l4-.02l-.06-11.94a11 11 0 0 0-3.563 5.482c-.262.948-.4 1.947-.397 2.978z");
}

.ltwsa8bld {
  d: path("M7.757 10.031c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.47c.27 0 .48-.22.48-.48v-3.24c0-2.36-1.91-4.27-4.27-4.27h-7.45a4.253 4.253 0 0 0-4.27 4.26v3.24c0 .27.21.49.48.49z");
}

.lvlvw7bgp {
  stop-color: var(--svg-color--513a64, #513A64);
  stop-opacity: 0;
}

.m1_q07_me {
  stop-color: var(--svg-color--6899f0, #6899F0);
}

.m27k_nb6m {
  fill: var(--svg-color--0d0b10, #0D0B10);
  d: path("M18.54 8.082a1.9 1.9 0 0 0-.701-.42c-.31-.097-.699-.123-1.236-.057a.283.283 0 1 0 .068.561c.491-.06.792-.029.998.036c.202.064.34.167.5.307a.283.283 0 0 0 .371-.427");
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mrp1fzb0j {
  d: path("M14.734 18.039c-1.216 0-2.198-.93-2.198-2.083v-2.589c0-1.142.982-2.073 2.198-2.073s2.197.93 2.197 2.083v2.59c-.01 1.142-.992 2.072-2.197 2.072");
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.n26l-i5_v {
  stop-color: var(--svg-color--d1978d, #D1978D);
  stop-opacity: 0;
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ndlc49hkf {
  d: path("M21.974 6.741H7.744v3.29h14.23z");
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.o1gf6ebie {
  stop-color: var(--svg-color--cf89ac, #CF89AC);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odxs-cbnv {
  stop-color: var(--svg-color--ad7062, #AD7062);
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oool1tdti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 28.611h1.797");
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
}

.p09lm7njz {
  stop-color: var(--svg-color--e4aa96, #E4AA96);
}

.p3_97vb4n {
  stop-color: var(--svg-color--465e8a, #465E8A);
  stop-opacity: 0;
}

.p64oiyb7x {
  stop-color: var(--svg-color--55406a, #55406A);
}

.p7prpqhjw {
  stop-color: var(--svg-color--5da7f2, #5DA7F2);
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pjsi77bhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.67 27.307h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.py0n-wnry {
  cx: 12.232px;
  cy: 9.819px;
  rx: 0.397px;
  ry: 0.201px;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.q9u3nxbxg {
  stop-color: var(--svg-color--513a64, #513A64);
}

.qgmif2bih {
  stop-color: var(--svg-color--57525e, #57525E);
  stop-opacity: 0;
}

.qo28zhh9b {
  stop-color: var(--svg-color--3a2252, #3A2252);
}

.qtzewq2gr {
  d: path("M22.13 25.326c0-.402.326-.732.727-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qv8wc6zla {
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qvxq5kbmq {
  stop-color: var(--svg-color--e4aa96, #E4AA96);
  stop-opacity: 0;
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
}

.r8mrl8bdh {
  stop-color: var(--svg-color--b27263, #B27263);
}

.rq76sybla {
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.rtj8_6bqg {
  stop-color: var(--svg-color--2a3765, #2A3765);
}

.rvb3y3bkj {
  fill: var(--svg-color--000, #000);
  d: path("M13.028 10.34a.52.52 0 0 0-.521-.521a.52.52 0 0 0-.464.761h.923a.5.5 0 0 0 .062-.24");
}

.s1a8ycb7r {
  stop-color: var(--svg-color--362d41, #362D41);
}

.s1rw4px-b {
  stop-color: var(--svg-color--465e8a, #465E8A);
}

.s21zh4b3w {
  stop-color: var(--svg-color--3d78d0, #3D78D0);
  stop-opacity: 0;
}

.s5pm96b_v {
  stop-color: var(--svg-color--3578e5, #3578E5);
  stop-opacity: 0;
}

.sb1phf9zd {
  d: path("M20.979 4.68H8.719v2.65h12.26z");
}

.sq-bwm1qa {
  stop-color: var(--svg-color--1f54c5, #1F54C5);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t6zrydbnh {
  fill: var(--svg-color--000, #000);
  d: path("M16.44 10.34c0-.29.231-.521.52-.521a.52.52 0 0 1 .464.76h-.922a.5.5 0 0 1-.062-.239");
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.tadvv5bzp {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.344 13.425c.402.21.88.33 1.39.33a3 3 0 0 0 1.39-.33a.21.21 0 0 1 .245.04a.19.19 0 0 1 .02.245m-3.045-.285l3.004.258m-3.004-.258a.21.21 0 0 0-.246.042a.19.19 0 0 0-.02.244m.266-.286l-.225.258m3.27.027l-.04-.027m.04.027l-.04-.027m.04.027a1.98 1.98 0 0 1-1.655.885a1.98 1.98 0 0 1-1.656-.884m3.27-.028a1.93 1.93 0 0 1-1.614.862a1.93 1.93 0 0 1-1.615-.862m-.041.028l.041-.028m-.041.028l.041-.028");
}

.tagaeklzk {
  d: path("M19.69 12.125c.342-.01.662-.127.923-.315v.95c0 .91-.543 1.722-1.367 2.059q.261-.556.352-1.204z");
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tm3a41odp {
  stop-color: var(--svg-color--bb7c70, #BB7C70);
}

.tpyby8h1l {
  stop-color: var(--svg-color--814b5f, #814B5F);
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.u_qgni50q {
  stop-color: var(--svg-color--7d4f4e, #7D4F4E);
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.uhvh9szrw {
  stop-color: var(--svg-color--e3b2a8, #E3B2A8);
}

.usq0mac0v {
  stop-color: var(--svg-color--493b3a, #493B3A);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.vm6kozbyx {
  d: path("M9.58 8.956a1.641 1.641 0 0 0 .142 3.263a80 80 0 0 1-.142-3.263");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vvma5rbrc {
  stroke: var(--svg-color--252325, #252325);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.365 8.21c-.22-.237-.796-.526-1.666-.4");
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wb_ynyb7f {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.238 10.478l-.647 1.875c-.111.386.155.771.53.771h.802c.376 0 .642-.391.531-.771l-.542-1.875c-.116-.415-.552-.415-.674 0");
}

.wg0ef3bbj {
  d: path("M9.536 9.63a.975.975 0 0 0 .085 1.916a79 79 0 0 1-.085-1.917");
}

.wg0u_rd0m {
  stop-color: var(--svg-color--c49888, #C49888);
}

.wp6rq3sqk {
  stop-color: var(--svg-color--6e5981, #6E5981);
}

.wqouu2b2u {
  d: path("M12.507 9.43a.91.91 0 0 0-.877 1.15h1.758a1 1 0 0 0 .033-.24a.916.916 0 0 0-.914-.91");
}

.wyyomf4yi {
  fill: var(--svg-color--e1ab97, #E1AB97);
  d: path("m14.344 10.248l-.542 1.875c-.11.385.155.77.53.77h.803c.376 0 .641-.39.53-.77l-.541-1.875c-.117-.415-.659-.415-.78 0");
}

.x1_659jhp {
  d: path("M19.752 12.218q.102-1.627.189-3.254a1.641 1.641 0 0 1-.189 3.254");
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.xuipl1bei {
  stop-color: var(--svg-color--dea69b, #DEA69B);
}

.y13139flk {
  stop-color: var(--svg-color--dd9ead, #DD9EAD);
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yd41utmlw {
  stop-color: var(--svg-color--32263f, #32263F);
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.ysugf1aqs {
  stop-color: var(--svg-color--b97985, #B97985);
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z-f4zlb4n {
  stop-color: var(--svg-color--251229, #251229);
}

.z2op5sb3v {
  stop-color: var(--svg-color--b28477, #B28477);
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.z88owpbip {
  stop-color: var(--svg-color--24132c, #24132C);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

</style>
