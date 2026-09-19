<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDGTqqc)" class="n4gi5xbcf"/><path fill="url(#iZS06yc)" class="fwzh_q90y"/><path fill="url(#iU4QItb)" class="fwzh_q90y"/><g filter="url(#iQvnTtd)"><path fill="url(#iOHMKid)" class="d21s5tb5g"/></g><path class="ct2-csn-n"/><path fill="url(#iA9k5wi)" class="rh86s7vxc"/><path fill="url(#iFBspBn)" class="jfdxq0biw"/><path fill="url(#iTrUtld)" class="jfdxq0biw"/><path fill="url(#ilAOUHc)" class="j4p1209iw"/><path fill="url(#iVeTq3C)" class="j4p1209iw"/><g filter="url(#iYP85Me)"><path fill="url(#iXRmVBb)" class="d4gy88zba"/><path fill="url(#iSVtU5d)" class="d4gy88zba"/><path fill="url(#iECnDgb)" class="d4gy88zba"/></g><path fill="url(#isNyJDb)" class="d4gy88zba"/><path fill="url(#iA7Wk7P)" class="d4gy88zba"/><path fill="url(#iKwws1b)" class="wna4bj1uj"/><path fill="url(#iEiXbsd)" class="x0xdvfbzb"/><path fill="url(#iFH4prb)" class="uzwu-7sft"/><path fill="url(#iaKgYPd)" class="itx0r6b2e"/><g filter="url(#iRMTVte)"><path class="kzguxzb7w"/><path fill="url(#iRoWpxb)" class="y7qlz64hx"/></g><g filter="url(#ilcVnlb)"><path fill="url(#iVyz57d)" class="z5k9t_ett"/></g><path fill="url(#imVKQAu)" class="wgy1q7bgx"/><path fill="url(#iXLnWCd)" class="wgy1q7bgx"/><path fill="url(#ilUlqqb)" class="wgy1q7bgx"/><path fill="url(#iC5Ff3c)" class="wgy1q7bgx"/><g filter="url(#i67LTNS)"><path fill="url(#i0Qrrac)" class="a3gz1ioyv"/></g><path fill="url(#iqkYhtK)" class="nve-5dbdy"/><path fill="url(#iyofx9b)" class="nve-5dbdy"/><path fill="url(#iXKEgde)" class="nve-5dbdy"/><path fill="url(#iYnVdqd)" class="nve-5dbdy"/><path fill="url(#iuQFale)" class="nve-5dbdy"/><g filter="url(#i5JvIwd)"><path class="bapcxobik"/></g><g filter="url(#ianMFYc)"><path fill="url(#iaGsE7L)" class="xsz_adbeh"/></g><g filter="url(#iMyDZFe)"><path fill="url(#iFFAT0b)" class="bta5cjbdu"/></g><path fill="url(#iiM0xIF)" class="bta5cjbdu"/><g filter="url(#iJ8UJnc)"><path class="blho51bao"/></g><g filter="url(#i3bLlGb)"><path class="a1wldw8lq"/><path fill="url(#iNPnlEz)" class="v6wir4bzo"/><path fill="url(#iLOewye)" class="v6wir4bzo"/><path fill="url(#iXN2YWV)" class="v6wir4bzo"/><path fill="url(#i4aisld)" class="v6wir4bzo"/><path fill="url(#ion750c)" class="v6wir4bzo"/></g><g filter="url(#iJJJMdM)"><path stroke="url(#iIlJHBe)" class="yeg4hck9j"/></g><path fill="url(#iXfeK0b)" class="cyvf4bctu"/><g filter="url(#isl0EqG)"><path class="xeada9b_s"/></g><g filter="url(#iWuGT0c)"><path class="bszw5t0oi"/></g><g filter="url(#i5Kk3cM)"><path class="gi6r79b6f"/></g><g filter="url(#ifUiL7b)"><path class="kp5zo0x3v"/></g><g filter="url(#isV5iAe)"><path fill="url(#iKL1i8z)" class="z2cv1gbif"/></g><path fill="url(#iwAuo3c)" class="ce79zxcds"/><path fill="url(#iua6s7Z)" class="ce79zxcds"/><path fill="url(#iyQPUbe)" class="zy_8cccga"/><path fill="url(#i6v6ghd)" class="zy_8cccga"/><path fill="url(#i40nYsc)" class="kyrtd_b2k"/><path fill="url(#iTxqmQm)" class="kyrtd_b2k"/><path fill="url(#i2iJ3od)" class="kyrtd_b2k"/><g filter="url(#iK5weAb)"><path class="a-n02u9ez"/></g><path class="tz2mehbfz"/><path fill="url(#iD2fmWd)" class="qssxzmbvc"/><path class="dy18of4jp"/><g filter="url(#ivGDjlb)"><path class="bbq7x5bgc"/><path fill="url(#iV4k8ac)" class="m5utybbaa"/></g><g filter="url(#i5byUBe)"><path fill="url(#iG5zhEb)" class="qt7g62m9w"/></g><path class="v6ti_6bru"/><path fill="url(#i7TqtHc)" class="onq8zj4lx"/><path class="a6soxiu1p"/><g filter="url(#i4Gi9ve)"><path fill="url(#ixZYcud)" class="nmusnlz6k"/></g><g filter="url(#ivSikyd)"><ellipse transform="rotate(-27.914 12.693 9.873)" class="msu6dk46p"/><ellipse fill="url(#ifNO5zb)" transform="rotate(-27.914 12.693 9.873)" class="hfv82gbxt"/></g><g filter="url(#iUlLSDb)"><path fill="url(#iwJYGET)" class="ix7_pubyn"/><path fill="url(#ipb9Dmc)" class="ix7_pubyn"/><path fill="url(#il1YQdd)" class="ix7_pubyn"/><path fill="url(#i38yMhb)" class="ix7_pubyn"/><path fill="url(#iiuUhIc)" class="ix7_pubyn"/></g><g filter="url(#i70Pdab)"><path stroke="url(#i0toKcd)" class="yikqznebw"/></g><g filter="url(#iIYFruc)"><path stroke="url(#iWyyU1b)" class="jpd7edpda"/></g><g filter="url(#i6i3chc)"><path stroke="url(#iMYMY3c)" class="xl6wrxczr"/></g><defs><radialGradient id="iDGTqqc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19 3.96)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iZS06yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 18.875 5.122)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iOHMKid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.50793 14.3416 0 15.813 14.317)" gradientUnits="userSpaceOnUse"><stop class="vo_-stf6h"/><stop offset="1" class="vghacj9nn"/></radialGradient><radialGradient id="iA9k5wi" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.112 16.285)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iTrUtld" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 2.969 25.247)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iVeTq3C" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.142 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iXRmVBb" cx="0" cy="0" r="1" gradientTransform="scale(3.73669 5.49005)rotate(90 .56 3.503)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iECnDgb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 14.327 19.551)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iA7Wk7P" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 14.575 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iKwws1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.102 19.652)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iEiXbsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.76526 -2.78533 0 15.113 16.695)" gradientUnits="userSpaceOnUse"><stop class="weo1_s1xr"/><stop offset=".442" class="x75-tty8m"/><stop offset=".836" class="uwr0-qq-p"/></radialGradient><radialGradient id="iFH4prb" cx="0" cy="0" r="1" gradientTransform="rotate(106.239 5.786 13.787)scale(3.29653 3.40165)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="k0h7iib9j"/><stop offset="1" class="pft2s7y0a"/><stop offset="1" class="d3t44e61i"/></radialGradient><radialGradient id="iaKgYPd" cx="0" cy="0" r="1" gradientTransform="matrix(.36775 3.36063 -1.96773 .21533 9.438 12.229)" gradientUnits="userSpaceOnUse"><stop class="vfxza6b6b"/><stop offset="1" class="ckj4lwxxs"/></radialGradient><radialGradient id="iRoWpxb" cx="0" cy="0" r="1" gradientTransform="rotate(-114.07 8.884 2.883)scale(1.73157)" gradientUnits="userSpaceOnUse"><stop class="jqq5_cbzl"/><stop offset="1" class="e4q48c0eh"/></radialGradient><radialGradient id="iVyz57d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41345 0 0 -2.09099 10.423 10.77)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="prkeaabuo"/><stop offset="1" class="r445c2j1q"/></radialGradient><radialGradient id="iXLnWCd" cx="0" cy="0" r="1" gradientTransform="rotate(-33.074 26.88 -25.838)scale(2.07337 1.66975)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ilUlqqb" cx="0" cy="0" r="1" gradientTransform="matrix(.86341 -2.14596 2.91895 1.17442 19.323 10.705)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="sxoyafbbn"/><stop offset=".972" class="tri7bg95c"/></radialGradient><radialGradient id="iC5Ff3c" cx="0" cy="0" r="1" gradientTransform="rotate(-47.534 23.848 -16.761)scale(2.11072 1.8094)" gradientUnits="userSpaceOnUse"><stop class="qrtt6bb6h"/><stop offset="1" class="jyn3bzb2d"/></radialGradient><radialGradient id="i0Qrrac" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 4.941 15.106)scale(1.11515)" gradientUnits="userSpaceOnUse"><stop class="zqtv86tqc"/><stop offset=".912" class="d1kj1wnus"/></radialGradient><radialGradient id="iyofx9b" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.122 11.69)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iuQFale" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.121 18.81)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iFFAT0b" cx="0" cy="0" r="1" gradientTransform="rotate(157.537 8.321 6.923)scale(7.03368 6.22718)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ekpjog9hc"/><stop offset="1" class="z15t62l8q"/></radialGradient><radialGradient id="iiM0xIF" cx="0" cy="0" r="1" gradientTransform="rotate(97.619 4.336 11.512)scale(8.62124 9.05183)" gradientUnits="userSpaceOnUse"><stop offset=".605" class="mxhpj29zu"/><stop offset=".972" class="ypf_dlp0n"/></radialGradient><radialGradient id="iLOewye" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22684 -.76458 0 15.646 12.237)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="i4aisld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68633 .69705 -1.06744 -2.58237 15.762 11.708)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iXfeK0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.32786 -1.17054 4.7739 9.49392 14.597 14.48)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iKL1i8z" cx="0" cy="0" r="1" gradientTransform="matrix(2.14063 0 0 .27812 17.563 7.075)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="yc0m-ob7p"/><stop offset="1" class="erb3s6b0r"/></radialGradient><radialGradient id="iwAuo3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 27.301 23.769)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iua6s7Z" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.71 23.618)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="i6v6ghd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 25.295 24.77)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="i40nYsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 25.318 21.59)" gradientUnits="userSpaceOnUse"><stop class="f1e16d8dl"/><stop offset="1" class="r_2nh8m3w"/><stop offset="1" class="pe7ydabrg"/></radialGradient><radialGradient id="iTxqmQm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 24.82 21.973)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="ajwv7ubbs"/><stop offset="1" class="ljk-gfbyr"/></radialGradient><radialGradient id="iD2fmWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 17.395 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iV4k8ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.164 10.055)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7TqtHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 12.968 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ifNO5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 12.677 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipb9Dmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.073 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="il1YQdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.073 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i38yMhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.073 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iiuUhIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.073 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><filter id="iQvnTtd" width="20.537" height="10.328" x="4.663" y="4.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1807" result="effect2_innerShadow_4002_1807"/></filter><filter id="iYP85Me" width="8" height="6.44" x="11.182" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="iRMTVte" width="3.44" height="3.34" x="8.542" y="8.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.439216 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="ilcVnlb" width="2.658" height="2.658" x="8.883" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".125"/></filter><filter id="i67LTNS" width="3.027" height="3.027" x="18.488" y="9.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".175"/></filter><filter id="i5JvIwd" width="8.45" height="4.612" x="10.912" y="25.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".125"/></filter><filter id="ianMFYc" width="8.05" height="4.28" x="11.062" y="25.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="iMyDZFe" width="10.869" height="10.18" x="9.994" y="6.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.439216 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="iJ8UJnc" width="3.871" height="4.695" x="13.053" y="9.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".5"/></filter><filter id="i3bLlGb" width="2.271" height="3.095" x="14.046" y="9.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".1"/></filter><filter id="iJJJMdM" width="3.833" height="1.572" x="13.205" y="13.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".05"/></filter><filter id="isl0EqG" width="2.195" height="1.016" x="16.761" y="7.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.137255 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="iWuGT0c" width="2.095" height=".766" x="16.811" y="7.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".075"/></filter><filter id="i5Kk3cM" width="2.195" height="1.016" x="11.401" y="7.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.137255 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="ifUiL7b" width="2.095" height=".766" x="11.451" y="7.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".075"/></filter><filter id="isV5iAe" width="4.103" height=".85" x="15.882" y="6.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.105882 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="iK5weAb" width="7.625" height="9.853" x="21.035" y="10.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.478431 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1807" result="effect2_innerShadow_4002_1807"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1807" result="effect3_innerShadow_4002_1807"/></filter><filter id="ivGDjlb" width=".795" height=".703" x="16.652" y="9.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".05"/></filter><filter id="i5byUBe" width=".898" height=".921" x="17.506" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".1"/></filter><filter id="i4Gi9ve" width=".995" height="1.05" x="12.998" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".1"/></filter><filter id="ivSikyd" width=".923" height=".712" x="12.231" y="9.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".05"/></filter><filter id="iUlLSDb" width="4.468" height="5.556" x="22.636" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1807"/></filter><filter id="i70Pdab" width="2.097" height=".3" x="23.006" y="25.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".05"/></filter><filter id="iIYFruc" width="2.097" height=".3" x="22.928" y="27.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".05"/></filter><filter id="i6i3chc" width="2.097" height=".3" x="23.006" y="28.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1807" stdDeviation=".05"/></filter><linearGradient id="iU4QItb" x1="15.102" x2="15.102" y1="4.01" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iFBspBn" x1="8.122" x2="4.531" y1="28.434" y2="28.434" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="ilAOUHc" x1="25.684" x2="22.142" y1="22.864" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iSVtU5d" x1="19.182" x2="18.247" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="isNyJDb" x1="11.182" x2="11.516" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="imVKQAu" x1="21.352" x2="21.782" y1="9.364" y2="11.631" gradientUnits="userSpaceOnUse"><stop class="rozhtxbew"/><stop offset="1" class="wdid2qbjr"/></linearGradient><linearGradient id="iqkYhtK" x1="16.344" x2="15.132" y1="29.122" y2="21.997" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iXKEgde" x1="22.195" x2="21.969" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iYnVdqd" x1="8.122" x2="8.246" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iaGsE7L" x1="12.969" x2="19.5" y1="28.341" y2="28.341" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="iNPnlEz" x1="16.017" x2="15.182" y1="11.6" y2="11.637" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iXN2YWV" x1="15.182" x2="15.182" y1="12.659" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ion750c" x1="15.182" x2="15.182" y1="10.145" y2="10.653" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iIlJHBe" x1="13.839" x2="14.193" y1="14.22" y2="13.315" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iyQPUbe" x1="24.792" x2="24.792" y1="21.591" y2="24.77" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="i2iJ3od" x1="24.82" x2="24.82" y1="22.294" y2="21.7" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="iG5zhEb" x1="18.185" x2="17.866" y1="10.025" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixZYcud" x1="13.723" x2="13.404" y1="10.024" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwJYGET" x1="26.664" x2="22.636" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="i0toKcd" x1="23.156" x2="24.866" y1="26.036" y2="26.036" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iWyyU1b" x1="23.078" x2="24.787" y1="27.341" y2="27.341" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iMYMY3c" x1="23.156" x2="24.866" y1="28.645" y2="28.645" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:farmer-medium" /></template>
<style>
.a-n02u9ez {
  fill: var(--svg-color--bfb2cd, #BFB2CD);
  d: path("M21.937 11.044a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.601");
}

.a1wldw8lq {
  fill: var(--svg-color--9e7169, #9E7169);
  d: path("m14.802 10.31l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.a3gz1ioyv {
  d: path("M20.002 11.753a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.a6soxiu1p {
  fill: var(--svg-color--000, #000);
  d: path("M13.484 10.391a.517.517 0 0 0-.518-.518a.516.516 0 0 0-.461.757h.917a.5.5 0 0 0 .062-.239");
}

.ajwv7ubbs {
  stop-color: var(--svg-color--92879d, #92879D);
  stop-opacity: 0;
}

.bapcxobik {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M18.602 25.81h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.bbq7x5bgc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.331 9.677c.064.086-.07.192-.224.306c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.blho51bao {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.609 10.535l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.bszw5t0oi {
  stroke: var(--svg-color--5a4343, #5A4343);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.706 8.216s-.625-.473-1.695-.344");
}

.bta5cjbdu {
  d: path("m20.352 8.96l.01-.11c.04-1.09-.83-2.04-1.93-2.04h-6.5c-1.14 0-2.03.97-1.93 2.1l.3 4.65a3.95 3.95 0 0 0 3.92 3.43h1.9c1.98 0 3.66-1.47 3.92-3.43z");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.ce79zxcds {
  d: path("M25.954 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.ckj4lwxxs {
  stop-color: var(--svg-color--31232d, #31232D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ct2-csn-n {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.112 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.cyvf4bctu {
  d: path("M15.122 13.69c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.d1kj1wnus {
  stop-color: var(--svg-color--a47562, #A47562);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d21s5tb5g {
  d: path("M10.745 4.81c-.849.03-2.678.228-4.101 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.094 1.781 1.445 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.882-4.93V9.23c0-.969-.239-2.123-1.476-3.086c-1.424-1.107-3.253-1.304-4.102-1.336z");
}

.d3t44e61i {
  stop-color: var(--svg-color--312835, #312835);
}

.d4gy88zba {
  d: path("m12.146 21.473l3.036-2.123l2.987 2.084c.42.325 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.594.823.964.563");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.dy18of4jp {
  fill: var(--svg-color--000, #000);
  d: path("M16.879 10.391c0-.288.23-.518.518-.518a.516.516 0 0 1 .462.757h-.918a.47.47 0 0 1-.062-.239");
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4q48c0eh {
  stop-color: var(--svg-color--81545e, #81545E);
  stop-opacity: 0;
}

.ekpjog9hc {
  stop-color: var(--svg-color--c3967d, #C3967D);
}

.erb3s6b0r {
  stop-color: var(--svg-color--4f3736, #4F3736);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.f1e16d8dl {
  stop-color: var(--svg-color--cbc1d6, #CBC1D6);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwzh_q90y {
  d: path("m9.282 5.55l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gi6r79b6f {
  stroke: var(--svg-color--482f2d, #482F2D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.651 8.278s.625-.473 1.696-.344");
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

.hfv82gbxt {
  cx: 12.693px;
  cy: 9.873px;
  rx: 0.395px;
  ry: 0.2px;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.itx0r6b2e {
  d: path("m9.252 10.19l-.01 2.69c0 .93.59 1.75 1.46 2.06l1.89.65v-5.43c-1.1 0-2.22 0-3.34.03");
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.ix7_pubyn {
  d: path("M22.636 25.306a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j4p1209iw {
  d: path("M22.142 29.98V18.01h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.jfdxq0biw {
  d: path("M8.122 29.98V18.01h-.007a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.jpd7edpda {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.078 27.263h1.797");
}

.jqq5_cbzl {
  stop-color: var(--svg-color--81545e, #81545E);
}

.jyn3bzb2d {
  stop-color: var(--svg-color--9a716b, #9A716B);
  stop-opacity: 0;
}

.k0h7iib9j {
  stop-color: var(--svg-color--604544, #604544);
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

.kp5zo0x3v {
  stroke: var(--svg-color--5a4343, #5A4343);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.651 8.216s.625-.473 1.696-.344");
}

.kyrtd_b2k {
  d: path("M24.058 19.989h1.524v1.734a.25.25 0 0 1-.25.25h-1.024a.25.25 0 0 1-.25-.25z");
}

.kzguxzb7w {
  fill: var(--svg-color--8a6160, #8A6160);
  d: path("M10.212 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljk-gfbyr {
  stop-color: var(--svg-color--92879d, #92879D);
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m5utybbaa {
  d: path("M17.331 9.677c.064.086-.07.192-.224.306c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.msu6dk46p {
  cx: 12.693px;
  cy: 9.873px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.mxhpj29zu {
  stop-color: var(--svg-color--91606d, #91606D);
  stop-opacity: 0;
}

.n4gi5xbcf {
  d: path("M21.102 5.91h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nmusnlz6k {
  d: path("M13.793 10.285c0-.293-.238-.488-.302-.547l-.293.283l.18.367z");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nve-5dbdy {
  d: path("M22.142 18.04c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.onq8zj4lx {
  d: path("M12.966 9.486a.905.905 0 0 0-.873 1.144h1.75a1 1 0 0 0 .032-.239a.91.91 0 0 0-.91-.905");
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.pe7ydabrg {
  stop-color: var(--svg-color--aa9ab9, #AA9AB9);
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.prkeaabuo {
  stop-color: var(--svg-color--734b49, #734B49);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qrtt6bb6h {
  stop-color: var(--svg-color--9a716b, #9A716B);
}

.qssxzmbvc {
  d: path("M17.398 9.486a.906.906 0 0 1 .872 1.144h-1.75a.91.91 0 0 1 .877-1.144");
}

.qt7g62m9w {
  d: path("M18.204 10.272a.85.85 0 0 0-.235-.47l-.263.29l.119.232z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r445c2j1q {
  stop-color: var(--svg-color--845b5a, #845B5A);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rh86s7vxc {
  d: path("M15.112 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rozhtxbew {
  stop-color: var(--svg-color--c19e89, #C19E89);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tz2mehbfz {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.608 9.21c.662 0 1.222.457 1.374 1.074a.278.278 0 0 1-.271.346h-2.264a.234.234 0 0 1-.23-.276c.127-.65.7-1.144 1.39-1.144");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uwr0-qq-p {
  stop-color: var(--svg-color--412d24, #412D24);
}

.uzwu-7sft {
  d: path("M17.622 10.25v5.35l1.89-.65c.88-.3 1.46-1.13 1.46-2.06v-2.53c-1.12-.04-2.24-.08-3.35-.11");
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v6ti_6bru {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.756 9.21c-.663 0-1.223.457-1.375 1.074a.278.278 0 0 0 .272.346h2.263c.145 0 .26-.132.231-.276a1.42 1.42 0 0 0-1.391-1.144");
}

.v6wir4bzo {
  d: path("m14.802 10.31l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vfxza6b6b {
  stop-color: var(--svg-color--523a38, #523A38);
}

.vghacj9nn {
  stop-color: var(--svg-color--633846, #633846);
}

.vo_-stf6h {
  stop-color: var(--svg-color--744f51, #744F51);
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wdid2qbjr {
  stop-color: var(--svg-color--a97e72, #A97E72);
}

.weo1_s1xr {
  stop-color: var(--svg-color--855965, #855965);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wgy1q7bgx {
  d: path("M20.002 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wna4bj1uj {
  d: path("m16.032 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x0xdvfbzb {
  d: path("M15.112 18.67c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x75-tty8m {
  stop-color: var(--svg-color--8f6864, #8F6864);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xeada9b_s {
  stroke: var(--svg-color--482f2d, #482F2D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.706 8.278s-.625-.473-1.695-.344");
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xl6wrxczr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.156 28.567h1.797");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xsz_adbeh {
  d: path("M18.602 25.81h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.y7qlz64hx {
  d: path("M10.212 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc0m-ob7p {
  stop-color: var(--svg-color--5c4241, #5C4241);
}

.yeg4hck9j {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.665 13.286c-.198-.106-.391.12-.275.301a2.07 2.07 0 0 0 1.732.943c.728 0 1.363-.38 1.732-.942a.2.2 0 0 0-.025-.256a.21.21 0 0 0-.25-.047v.001a3.1 3.1 0 0 1-1.457.354a3.1 3.1 0 0 1-1.457-.354Z");
}

.yikqznebw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.156 25.958h1.797");
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.ypf_dlp0n {
  stop-color: var(--svg-color--7b565d, #7B565D);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.z15t62l8q {
  stop-color: var(--svg-color--916663, #916663);
}

.z2cv1gbif {
  d: path("M17.592 7.61h2.392c-.35-.48-.922-.8-1.552-.8h-2.55c.42.5 1.05.8 1.71.8");
}

.z5k9t_ett {
  d: path("M10.212 11.67a1.08 1.08 0 1 0 0-2.16a1.08 1.08 0 0 0 0 2.16");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zqtv86tqc {
  stop-color: var(--svg-color--b08975, #B08975);
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zy_8cccga {
  d: path("M25.295 21.77h-1v3h1z");
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
