<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#izEa4se)" class="bhzh2_30j"/><path fill="url(#iXP4BAb)" class="iglslg_1z"/><path fill="url(#ipFHjMH)" class="iglslg_1z"/><g filter="url(#iEo1wud)"><path fill="url(#iKc7kLc)" class="q7ac_5bxt"/></g><path class="i3m2dpo3l"/><path fill="url(#iHwegfd)" class="mnb08mbgb"/><path fill="url(#i7iaydc)" class="dzkgcbfip"/><path fill="url(#iLGH4Op)" class="dzkgcbfip"/><path fill="url(#iAPh9ld)" class="jkvptubre"/><path fill="url(#ifDeZvd)" class="jkvptubre"/><g filter="url(#igp3zMc)"><path fill="url(#inuuq9d)" class="gc_kl0btp"/><path fill="url(#iBWn0Nk)" class="gc_kl0btp"/><path fill="url(#iCs7reB)" class="gc_kl0btp"/></g><path fill="url(#i4H5mJe)" class="gc_kl0btp"/><path fill="url(#iXlygyx)" class="gc_kl0btp"/><path fill="url(#io6syUd)" class="as4-occef"/><path fill="url(#iiknVJb)" class="y-j69wceb"/><path fill="url(#iIstepb)" class="y-j69wceb"/><path fill="url(#i5pXVLc)" class="qiomox_0w"/><path fill="url(#itfpmxb)" class="qha-pbcyt"/><g filter="url(#iVEs9sd)"><path class="p1ci_qs4u"/><path fill="url(#iZJUmCb)" class="z9qe_sb7n"/></g><g filter="url(#ixAwKng)"><path fill="url(#iFLOBvd)" class="dt75rhbjd"/></g><path fill="url(#iar1a1b)" class="xospg6bke"/><path fill="url(#iRxxQzb)" class="xospg6bke"/><g filter="url(#ikGQMtc)"><path fill="url(#ivNpFme)" class="x-dcoebpj"/></g><path fill="url(#ilzdr4c)" class="x2tlj95dr"/><path fill="url(#iDuSmmc)" class="x2tlj95dr"/><path fill="url(#ipnWAOb)" class="x2tlj95dr"/><path fill="url(#i1elHHR)" class="x2tlj95dr"/><path fill="url(#iPxrkqn)" class="x2tlj95dr"/><g filter="url(#iukUo6b)"><path class="cy0k7acty"/></g><g filter="url(#iupA1Cc)"><path fill="url(#i92pcBN)" class="qnaaoobgo"/></g><g filter="url(#iSUCgEz)"><path fill="url(#iwm78Fd)" class="p5odw4twa"/></g><path fill="url(#i8F0Ome)" class="p5odw4twa"/><path fill="url(#i3Horbe)" class="p5odw4twa"/><path fill="url(#iddaXfb)" class="p5odw4twa"/><path fill="url(#iDpo2Ec)" class="p5odw4twa"/><g filter="url(#inN01xd)"><path class="ujctgjcrq"/></g><g filter="url(#i1MF4Xd)"><path fill="url(#iEgU5Yb)" class="x7z1ydbqm"/><path fill="url(#iHwPLqc)" class="x7z1ydbqm"/><path fill="url(#ino0fwd)" class="x7z1ydbqm"/><path fill="url(#iunHivZ)" class="x7z1ydbqm"/></g><g filter="url(#iPhzmFe)"><path stroke="url(#iNErvCd)" class="xxz3inbzx"/></g><path fill="url(#iTHKO5m)" class="z5bx46zig"/><g filter="url(#iMhgWae)"><path class="uv_6gpbwf"/></g><g filter="url(#iXxfOEd)"><path class="ncoadkb2t"/></g><g filter="url(#ihti0gb)"><path class="i83-07zjn"/></g><g filter="url(#iCaX4Vb)"><path class="a22ep0bfh"/></g><g filter="url(#iJ6UW6F)"><path fill="url(#idRB5gk)" class="rk8oeacxe"/></g><path fill="url(#i3KYEnb)" class="xq-jf3bvd"/><path fill="url(#i13apfb)" class="xq-jf3bvd"/><path fill="url(#i6R5QGt)" class="vw-edwnzm"/><path fill="url(#igrBzDc)" class="vw-edwnzm"/><path fill="url(#iNmx9gE)" class="qjwig99ht"/><path fill="url(#i84seYd)" class="qjwig99ht"/><path fill="url(#iiGVVHb)" class="qjwig99ht"/><g filter="url(#iAFQP2d)"><path class="zkjihrb3l"/></g><path class="nlqy_2bud"/><path fill="url(#itxqq0d)" class="gx-o-vbay"/><path class="n4ns_4b3h"/><g filter="url(#i3kGGcb)"><path class="gllgbgbnw"/><path fill="url(#ixp7u1b)" class="u4ud7kbfc"/></g><g filter="url(#iv70u1c)"><path fill="url(#iqZlnte)" class="ut8-owbnz"/></g><path class="agra3ce6f"/><path fill="url(#iztFVWb)" class="oh5w5xeke"/><path class="gh2neqbwj"/><g filter="url(#iZF0kre)"><path fill="url(#isNRNok)" class="tb0p5-b_n"/></g><g filter="url(#i16VzSc)"><ellipse transform="rotate(-27.914 12.732 9.896)" class="y-pxwfy0b"/><ellipse fill="url(#ifOEHgc)" transform="rotate(-27.914 12.732 9.896)" class="bixecvv0v"/></g><g filter="url(#i35vTke)"><path fill="url(#ifmvcfd)" class="jhnr4cc6c"/><path fill="url(#iiQ4xte)" class="jhnr4cc6c"/><path fill="url(#iyG2sCb)" class="jhnr4cc6c"/><path fill="url(#iFVvsAA)" class="jhnr4cc6c"/><path fill="url(#iF1Mhlc)" class="jhnr4cc6c"/></g><g filter="url(#iQ9Xtte)"><path stroke="url(#iEUnP6c)" class="escgodq_r"/></g><g filter="url(#ifpuTnd)"><path stroke="url(#ibUy5YX)" class="h61997bck"/></g><g filter="url(#idNuDYA)"><path stroke="url(#iZPdC7b)" class="jomq5_onk"/></g><defs><radialGradient id="izEa4se" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.04 3.983)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iXP4BAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 18.914 5.145)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iKc7kLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.50793 14.3416 0 15.852 14.34)" gradientUnits="userSpaceOnUse"><stop class="l32yn2btk"/><stop offset="1" class="js9stk9vk"/></radialGradient><radialGradient id="iHwegfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.15 16.308)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iLGH4Op" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.008 25.27)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="ifDeZvd" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.18 24.733)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="inuuq9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 15.22 16.177)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iCs7reB" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 14.366 19.575)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iXlygyx" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 14.614 15.993)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="io6syUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.14 19.675)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iiknVJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87968 -1.90863 0 15.15 16.814)" gradientUnits="userSpaceOnUse"><stop class="ztiay3bsr"/><stop offset="1" class="d4abicb0m"/></radialGradient><radialGradient id="iIstepb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.28845 -2.56488 0 15.15 15.353)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="xcfgjsbuv"/><stop offset="1" class="h3ackr9-s"/></radialGradient><radialGradient id="i5pXVLc" cx="0" cy="0" r="1" gradientTransform="rotate(106.239 5.797 13.813)scale(3.29653 3.40165)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="bur65zjfo"/><stop offset="1" class="msd2itfez"/></radialGradient><radialGradient id="itfpmxb" cx="0" cy="0" r="1" gradientTransform="matrix(.36775 3.36063 -1.96773 .21533 9.477 12.253)" gradientUnits="userSpaceOnUse"><stop class="go1r3o_fh"/><stop offset="1" class="nhconhojc"/></radialGradient><radialGradient id="iZJUmCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.99999 -1.375 1.3434 -.977 10.6 12.126)" gradientUnits="userSpaceOnUse"><stop class="wc81wbc4w"/><stop offset="1" class="r1r_vbb7o"/></radialGradient><radialGradient id="iFLOBvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41345 0 0 -2.09099 10.462 10.794)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="yyk4p6yip"/><stop offset="1" class="e3i87pb5c"/></radialGradient><radialGradient id="iRxxQzb" cx="0" cy="0" r="1" gradientTransform="rotate(-51.009 22.998 -15.293)scale(1.68866)" gradientUnits="userSpaceOnUse"><stop class="vl2cjyt3c"/><stop offset="1" class="bx_7xxbew"/></radialGradient><radialGradient id="ivNpFme" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 4.95 15.137)scale(1.11515)" gradientUnits="userSpaceOnUse"><stop class="bg0uvkbxl"/><stop offset=".912" class="npel8zblz"/></radialGradient><radialGradient id="iDuSmmc" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.139 11.707)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iPxrkqn" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.16 18.833)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iwm78Fd" cx="0" cy="0" r="1" gradientTransform="rotate(163.348 8.568 6.912)scale(7.30642 10.5083)" gradientUnits="userSpaceOnUse"><stop class="xkci-rbab"/><stop offset=".821" class="k7gd4eb0c"/></radialGradient><radialGradient id="i8F0Ome" cx="0" cy="0" r="1" gradientTransform="matrix(-.64868 10.43686 -10.58877 -.65812 16.217 6.833)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="u_u21vb3i"/><stop offset="1" class="z3zt30oyc"/></radialGradient><radialGradient id="i3Horbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13517 1.69539 0 17.603 9.501)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xw_ywbgxb"/><stop offset="1" class="xbusw-bzo"/></radialGradient><radialGradient id="iddaXfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.32683 1.39666 0 13.003 9.73)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="ggvs2lbho"/><stop offset="1" class="t_r0nmbhs"/></radialGradient><radialGradient id="iDpo2Ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.37883 2.45794 -2.60198 1.45962 16.236 6.225)" gradientUnits="userSpaceOnUse"><stop class="z0k047bou"/><stop offset="1" class="nnluv8b2p"/></radialGradient><radialGradient id="iTHKO5m" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.78645 3.09358 0 15.16 14.412)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="idRB5gk" cx="0" cy="0" r="1" gradientTransform="matrix(2.14063 0 0 .27812 17.602 7.099)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="khugmwohe"/><stop offset="1" class="uvgyiob-s"/></radialGradient><radialGradient id="i3KYEnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 27.34 23.792)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="i13apfb" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.75 23.641)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="igrBzDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 25.334 24.794)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iNmx9gE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 25.357 21.614)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="i84seYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 24.86 21.997)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="itxqq0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 17.434 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ixp7u1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.203 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iztFVWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 13.007 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ifOEHgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 12.716 10.216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiQ4xte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.112 25.308)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iyG2sCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.112 26.602)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iFVvsAA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.112 27.852)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iF1Mhlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.112 29.204)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><filter id="iEo1wud" width="20.537" height="10.328" x="4.702" y="4.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1810" result="effect2_innerShadow_4002_1810"/></filter><filter id="igp3zMc" width="8" height="6.44" x="11.221" y="15.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="iVEs9sd" width="3.44" height="3.34" x="8.581" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="ixAwKng" width="2.658" height="2.658" x="8.922" y="9.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".125"/></filter><filter id="ikGQMtc" width="2.827" height="2.827" x="18.627" y="9.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".125"/></filter><filter id="iukUo6b" width="8.45" height="4.612" x="10.951" y="25.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".125"/></filter><filter id="iupA1Cc" width="8.05" height="4.28" x="11.101" y="25.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="iSUCgEz" width="10.869" height="10.18" x="10.033" y="6.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.611765 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="inN01xd" width="3.871" height="4.695" x="13.092" y="9.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".5"/></filter><filter id="i1MF4Xd" width="2.071" height="2.895" x="14.185" y="9.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><filter id="iPhzmFe" width="3.833" height="1.572" x="13.244" y="13.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><filter id="iMhgWae" width="2.195" height="1.016" x="16.799" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="iXxfOEd" width="2.095" height=".766" x="16.85" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".075"/></filter><filter id="ihti0gb" width="2.195" height="1.016" x="11.44" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="iCaX4Vb" width="2.095" height=".766" x="11.49" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".075"/></filter><filter id="iJ6UW6F" width="4.103" height=".85" x="15.921" y="6.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.729412 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="iAFQP2d" width="7.625" height="9.853" x="21.074" y="10.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1810" result="effect2_innerShadow_4002_1810"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1810" result="effect3_innerShadow_4002_1810"/></filter><filter id="i3kGGcb" width=".795" height=".703" x="16.691" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><filter id="iv70u1c" width=".898" height=".921" x="17.545" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".1"/></filter><filter id="iZF0kre" width=".995" height="1.05" x="13.037" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".1"/></filter><filter id="i16VzSc" width=".923" height=".712" x="12.27" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><filter id="i35vTke" width="4.468" height="5.556" x="22.675" y="24.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1810"/></filter><filter id="iQ9Xtte" width="2.097" height=".3" x="23.045" y="25.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><filter id="ifpuTnd" width="2.097" height=".3" x="22.967" y="27.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><filter id="idNuDYA" width="2.097" height=".3" x="23.045" y="28.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1810" stdDeviation=".05"/></filter><linearGradient id="ipFHjMH" x1="15.141" x2="15.141" y1="4.033" y2="4.087" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="i7iaydc" x1="8.161" x2="4.57" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iAPh9ld" x1="25.723" x2="22.181" y1="22.888" y2="29.194" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iBWn0Nk" x1="19.221" x2="18.286" y1="18.52" y2="18.52" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="i4H5mJe" x1="11.221" x2="11.555" y1="18.52" y2="18.52" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iar1a1b" x1="21.147" x2="20.041" y1="9.783" y2="12.283" gradientUnits="userSpaceOnUse"><stop class="xfxz_xbmx"/><stop offset="1" class="cegy3obbl"/></linearGradient><linearGradient id="ilzdr4c" x1="16.383" x2="15.171" y1="29.145" y2="22.02" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="ipnWAOb" x1="22.234" x2="22.008" y1="29.677" y2="29.677" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="i1elHHR" x1="8.161" x2="8.285" y1="29.677" y2="29.677" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="i92pcBN" x1="13.008" x2="19.539" y1="28.364" y2="28.364" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="iEgU5Yb" x1="15.221" x2="16.073" y1="11.766" y2="11.766" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iHwPLqc" x1="14.152" x2="15.222" y1="11.622" y2="11.685" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ino0fwd" x1="15.221" x2="15.221" y1="12.137" y2="12.929" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iunHivZ" x1="15.221" x2="15.221" y1="10.048" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iNErvCd" x1="13.878" x2="14.232" y1="14.244" y2="13.338" gradientUnits="userSpaceOnUse"><stop class="hq16hab0i"/><stop offset="1" class="iokwoek-x"/></linearGradient><linearGradient id="i6R5QGt" x1="24.831" x2="24.831" y1="21.614" y2="24.794" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iiGVVHb" x1="24.859" x2="24.859" y1="22.317" y2="21.723" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="iqZlnte" x1="18.224" x2="17.905" y1="10.048" y2="10.244" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isNRNok" x1="13.762" x2="13.443" y1="10.048" y2="10.244" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifmvcfd" x1="26.703" x2="22.675" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="nfkkf0b1d"/></linearGradient><linearGradient id="iEUnP6c" x1="23.195" x2="24.904" y1="26.059" y2="26.059" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="ibUy5YX" x1="23.117" x2="24.826" y1="27.364" y2="27.364" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iZPdC7b" x1="23.195" x2="24.904" y1="28.669" y2="28.669" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:farmer-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a22ep0bfh {
  stroke: var(--svg-color--a26d45, #A26D45);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.69 8.24s.625-.474 1.696-.345");
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.agra3ce6f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.795 9.233c-.663 0-1.223.457-1.375 1.075a.278.278 0 0 0 .272.345h2.264a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.391-1.145");
}

.as4-occef {
  d: path("m16.07 19.713l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bg0uvkbxl {
  stop-color: var(--svg-color--dba889, #DBA889);
}

.bhzh2_30j {
  d: path("M21.14 5.933h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.bixecvv0v {
  cx: 12.732px;
  cy: 9.896px;
  rx: 0.395px;
  ry: 0.2px;
}

.bur65zjfo {
  stop-color: var(--svg-color--ffe7b4, #FFE7B4);
}

.bx_7xxbew {
  stop-color: var(--svg-color--cc9981, #CC9981);
  stop-opacity: 0;
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.cegy3obbl {
  stop-color: var(--svg-color--d9a385, #D9A385);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cy0k7acty {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M18.64 25.834H11.7a.49.49 0 0 0-.5.491v3.62h7.95v-3.62a.513.513 0 0 0-.51-.491");
}

.d4abicb0m {
  stop-color: var(--svg-color--b48574, #B48574);
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dt75rhbjd {
  d: path("M10.25 11.693a1.08 1.08 0 1 0 0-2.159a1.08 1.08 0 0 0 0 2.159");
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.dzkgcbfip {
  d: path("M8.16 30.003v-11.97h-.006a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3i87pb5c {
  stop-color: var(--svg-color--bd826e, #BD826E);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.escgodq_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.195 25.981h1.797");
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
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

.gc_kl0btp {
  d: path("m12.185 21.497l3.036-2.124l2.987 2.085c.42.324 1.013.465 1.013-.355v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.691c0 .953.594.823.964.563");
}

.ggvs2lbho {
  stop-color: var(--svg-color--c4877b, #C4877B);
}

.gh2neqbwj {
  fill: var(--svg-color--000, #000);
  d: path("M13.523 10.415a.516.516 0 0 0-.518-.519a.516.516 0 0 0-.461.757h.918a.5.5 0 0 0 .061-.238");
}

.gllgbgbnw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.37 9.7c.064.087-.07.192-.224.307c-.153.114-.267.195-.331.109c-.065-.087.007-.25.16-.364c.154-.115.33-.138.395-.051");
}

.go1r3o_fh {
  stop-color: var(--svg-color--eabf94, #EABF94);
}

.gx-o-vbay {
  d: path("M17.437 9.51a.905.905 0 0 1 .872 1.143h-1.75a.91.91 0 0 1 .877-1.144");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3ackr9-s {
  stop-color: var(--svg-color--805333, #805333);
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h61997bck {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.117 27.286h1.797");
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hq16hab0i {
  stop-color: var(--svg-color--cf9a8c, #CF9A8C);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.i3m2dpo3l {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.15 15.523c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.i83-07zjn {
  stroke: var(--svg-color--8c5829, #8C5829);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.69 8.302s.625-.473 1.696-.344");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.iglslg_1z {
  d: path("m9.32 5.573l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.iokwoek-x {
  stop-color: var(--svg-color--cf9a8c, #CF9A8C);
  stop-opacity: 0;
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jhnr4cc6c {
  d: path("M22.675 25.329c0-.401.325-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.jkvptubre {
  d: path("M22.18 30.003v-11.97h.007a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.jomq5_onk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.195 28.59h1.797");
}

.js9stk9vk {
  stop-color: var(--svg-color--6f444a, #6F444A);
}

.k7gd4eb0c {
  stop-color: var(--svg-color--cc927e, #CC927E);
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

.khugmwohe {
  stop-color: var(--svg-color--f0cfa8, #F0CFA8);
}

.l32yn2btk {
  stop-color: var(--svg-color--7d5653, #7D5653);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
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

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnb08mbgb {
  d: path("M15.15 15.523c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.msd2itfez {
  stop-color: var(--svg-color--cbae89, #CBAE89);
}

.n4ns_4b3h {
  fill: var(--svg-color--000, #000);
  d: path("M16.918 10.415c0-.288.23-.519.519-.519a.516.516 0 0 1 .46.757h-.917a.47.47 0 0 1-.062-.238");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.ncoadkb2t {
  stroke: var(--svg-color--a26d45, #A26D45);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.745 8.24s-.625-.474-1.695-.345");
}

.nfkkf0b1d {
  stop-color: var(--svg-color--c4907c, #C4907C);
}

.nhconhojc {
  stop-color: var(--svg-color--dcab88, #DCAB88);
}

.nlqy_2bud {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.647 9.233c.662 0 1.222.457 1.374 1.075a.278.278 0 0 1-.271.345h-2.264a.234.234 0 0 1-.23-.275c.127-.65.7-1.145 1.39-1.145");
}

.nnluv8b2p {
  stop-color: var(--svg-color--d6a28d, #D6A28D);
  stop-opacity: 0;
}

.npel8zblz {
  stop-color: var(--svg-color--d6a080, #D6A080);
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh5w5xeke {
  d: path("M13.005 9.51a.906.906 0 0 0-.873 1.143h1.75a1 1 0 0 0 .032-.238a.91.91 0 0 0-.91-.906");
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.p1ci_qs4u {
  fill: var(--svg-color--c08675, #C08675);
  d: path("M10.25 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.p5odw4twa {
  d: path("m20.39 8.984l.01-.11c.04-1.09-.83-2.04-1.93-2.04h-6.5c-1.14 0-2.03.97-1.93 2.1l.3 4.65a3.95 3.95 0 0 0 3.92 3.43h1.9c1.98 0 3.66-1.47 3.92-3.43z");
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

.q7ac_5bxt {
  d: path("M10.784 4.833c-.849.031-2.678.228-4.101 1.336c-1.238.962-1.477 2.117-1.477 3.086v.476c-.094 1.781 1.445 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.882-4.93v-.476c0-.97-.239-2.124-1.476-3.086c-1.424-1.108-3.253-1.305-4.102-1.336z");
}

.qha-pbcyt {
  d: path("m9.29 10.214l-.01 2.69c0 .93.59 1.75 1.46 2.06l1.89.65v-5.43c-1.1 0-2.22 0-3.34.03");
}

.qiomox_0w {
  d: path("M17.66 10.273v5.35l1.89-.65c.88-.3 1.46-1.13 1.46-2.06v-2.53c-1.12-.04-2.24-.08-3.35-.11");
}

.qjwig99ht {
  d: path("M24.097 20.013h1.524v1.734a.25.25 0 0 1-.25.25h-1.024a.25.25 0 0 1-.25-.25z");
}

.qnaaoobgo {
  d: path("M18.64 25.834H11.7c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r1r_vbb7o {
  stop-color: var(--svg-color--bf8271, #BF8271);
  stop-opacity: 0;
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rk8oeacxe {
  d: path("M17.63 7.634h2.393c-.35-.48-.922-.8-1.552-.8h-2.55c.42.5 1.05.8 1.71.8");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.t_r0nmbhs {
  stop-color: var(--svg-color--c4877b, #C4877B);
  stop-opacity: 0;
}

.tb0p5-b_n {
  d: path("M13.832 10.308c0-.292-.238-.487-.302-.546l-.293.283l.18.366z");
}

.u_u21vb3i {
  stop-color: var(--svg-color--be8584, #BE8584);
  stop-opacity: 0;
}

.u4ud7kbfc {
  d: path("M17.37 9.7c.064.087-.07.192-.224.307c-.153.114-.267.195-.331.109c-.065-.087.007-.25.16-.364c.154-.115.33-.138.395-.051");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.ujctgjcrq {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.648 10.558l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.ut8-owbnz {
  d: path("M18.243 10.296a.85.85 0 0 0-.235-.47l-.263.29l.119.231z");
}

.uv_6gpbwf {
  stroke: var(--svg-color--8c5829, #8C5829);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.745 8.302s-.625-.473-1.695-.344");
}

.uvgyiob-s {
  stop-color: var(--svg-color--f0c9a0, #F0C9A0);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vl2cjyt3c {
  stop-color: var(--svg-color--cc9981, #CC9981);
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.vw-edwnzm {
  d: path("M25.334 21.794h-1v3h1z");
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wc81wbc4w {
  stop-color: var(--svg-color--bf8271, #BF8271);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.x-dcoebpj {
  d: path("M20.04 11.777a1.163 1.163 0 1 0 0-2.327a1.163 1.163 0 0 0 0 2.327");
}

.x2tlj95dr {
  d: path("M22.18 18.064c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x7z1ydbqm {
  d: path("m14.84 10.333l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.xbusw-bzo {
  stop-color: var(--svg-color--e1a489, #E1A489);
  stop-opacity: 0;
}

.xcfgjsbuv {
  stop-color: var(--svg-color--805333, #805333);
  stop-opacity: 0;
}

.xfxz_xbmx {
  stop-color: var(--svg-color--dcaf93, #DCAF93);
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xkci-rbab {
  stop-color: var(--svg-color--f7c09c, #F7C09C);
}

.xospg6bke {
  d: path("M20.04 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.xq-jf3bvd {
  d: path("M25.993 23.144c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.xw_ywbgxb {
  stop-color: var(--svg-color--e1a489, #E1A489);
}

.xxz3inbzx {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.704 13.31c-.198-.106-.391.12-.275.3a2.07 2.07 0 0 0 1.732.944a2.07 2.07 0 0 0 1.732-.943a.2.2 0 0 0-.025-.256a.21.21 0 0 0-.25-.046a3.1 3.1 0 0 1-1.457.355a3.1 3.1 0 0 1-1.457-.354Z");
}

.y-j69wceb {
  d: path("M15.15 18.693c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y-pxwfy0b {
  cx: 12.732px;
  cy: 9.896px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yyk4p6yip {
  stop-color: var(--svg-color--b67862, #B67862);
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z0k047bou {
  stop-color: var(--svg-color--d6a28d, #D6A28D);
}

.z3zt30oyc {
  stop-color: var(--svg-color--a67674, #A67674);
}

.z5bx46zig {
  d: path("M15.16 13.714c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.z9qe_sb7n {
  d: path("M10.25 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zkjihrb3l {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M21.976 11.067a.6.6 0 0 0-.602.602v6.851a1.5 1.5 0 0 0 1.5 1.5H27a1.5 1.5 0 0 0 1.5-1.5v-6.85a.602.602 0 1 0-1.203 0v4.449a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.6");
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.ztiay3bsr {
  stop-color: var(--svg-color--aa7876, #AA7876);
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
