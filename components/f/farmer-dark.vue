<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irEGmjb)" class="ybi_ymbzs"/><path fill="url(#iDlYaab)" class="w7k27yp0g"/><path fill="url(#iVMolOd)" class="w7k27yp0g"/><g filter="url(#i8NF4Ke)"><path fill="url(#iHYvMVc)" class="v8kh6dbqe"/><path fill="url(#ig9vVVc)" class="v8kh6dbqe"/></g><path class="b75_wpb8k"/><path fill="url(#i0miImb)" class="xiqrb2bni"/><path fill="url(#iSVnEyb)" class="w29231b4u"/><path fill="url(#idecHKc)" class="w29231b4u"/><path fill="url(#iytNNTc)" class="t0ml3mcnn"/><path fill="url(#iFGpAuD)" class="t0ml3mcnn"/><g filter="url(#i5lAcCc)"><path fill="url(#i3x6dVc)" class="d5ycxbcbt"/><path fill="url(#iyfgqhc)" class="d5ycxbcbt"/><path fill="url(#iCzhvqb)" class="d5ycxbcbt"/></g><path fill="url(#iqly9hd)" class="d5ycxbcbt"/><path fill="url(#icZHkOd)" class="d5ycxbcbt"/><path fill="url(#i10nBHd)" class="j5lippbik"/><path fill="url(#iUYlqpc)" class="ek7xw4b6q"/><path fill="url(#iYBCXPv)" class="uywde0klz"/><path fill="url(#igT1Aoe)" class="ven7bix4o"/><path fill="url(#iC70Uzb)" class="g5-i25boa"/><path fill="url(#iNGLDge)" class="g5-i25boa"/><g filter="url(#iHvS7Oe)"><path fill="url(#i4eOq0b)" class="r416lacsv"/></g><path fill="url(#iR93tBZ)" class="or181q_tu"/><path fill="url(#irpe6nb)" class="or181q_tu"/><path fill="url(#i0c4J2b)" class="or181q_tu"/><path fill="url(#i05ugEd)" class="or181q_tu"/><g filter="url(#iDD8Egc)"><path fill="url(#iK87wRd)" class="fb4b6ibbm"/></g><path fill="url(#iT1MBrd)" class="x2lxohqli"/><path fill="url(#iUBpvne)" class="x2lxohqli"/><path fill="url(#io7tJwE)" class="x2lxohqli"/><path fill="url(#iP2XIAc)" class="x2lxohqli"/><path fill="url(#iey3g0b)" class="x2lxohqli"/><g filter="url(#iQ20vOE)"><path class="sbcqa9buf"/></g><g filter="url(#icZLspc)"><path fill="url(#iUPlhmz)" class="p20764brf"/></g><g filter="url(#iEIvJBU)"><path fill="url(#iR4A6ek)" class="mwmfdtbeb"/></g><path fill="url(#io5aNLb)" class="mwmfdtbeb"/><path fill="url(#iwtYXPd)" class="mwmfdtbeb"/><path fill="url(#i1tbkvf)" class="mwmfdtbeb"/><path fill="url(#it4wuUc)" class="mwmfdtbeb"/><path fill="url(#iMmrm5b)" class="mwmfdtbeb"/><path fill="url(#iZ3lSse)" class="mwmfdtbeb"/><g filter="url(#iQ6flCe)"><path class="a23r32zth"/></g><g filter="url(#izYt6ib)"><path class="ed1dgs27p"/><path fill="url(#iQHyaXl)" class="kbq762bbe"/><path fill="url(#iRbL9Fc)" class="kbq762bbe"/><path fill="url(#idXTCTh)" class="kbq762bbe"/><path fill="url(#iknWdCb)" class="kbq762bbe"/><path fill="url(#iYaMVid)" class="kbq762bbe"/></g><g filter="url(#iHMylNc)"><path stroke="url(#iDRJLSb)" class="t9ltvac_b"/></g><path class="hliw7p2yd"/><g filter="url(#iSfgE4b)"><path class="j0mjhicuv"/></g><g filter="url(#iz51mpd)"><path class="kchpczmzf"/></g><g filter="url(#iM4jXdd)"><path class="tyab5j04g"/></g><g filter="url(#igp4Aac)"><path class="msktp5b2o"/></g><g filter="url(#iqgO9dc)"><path fill="url(#i2ewT8c)" class="cvjsb-a9z"/></g><path fill="url(#iyTL6td)" class="guv-zxbmy"/><path fill="url(#iJEbbub)" class="guv-zxbmy"/><path fill="url(#iKwHkib)" class="qem3izvox"/><path fill="url(#iFT09oe)" class="qem3izvox"/><path fill="url(#i5EFKMl)" class="k3hh8cmzu"/><path fill="url(#iXstkgd)" class="k3hh8cmzu"/><path fill="url(#i6Wm2kO)" class="k3hh8cmzu"/><g filter="url(#i3JkxGe)"><path class="m8928m_ok"/></g><path class="b4i7app5l"/><path fill="url(#iUnKlDX)" class="tnmr6xw7v"/><path class="f6dcfqkjw"/><g filter="url(#iomuude)"><path class="ye_0_ib9j"/><path fill="url(#i6PAMSc)" class="v82ve8b3o"/></g><g filter="url(#iJiv8ge)"><path fill="url(#i4PraBb)" class="qk4zjubee"/></g><path class="vptu-acpa"/><path fill="url(#ih2TDcb)" class="m7gf2ccaq"/><path class="w390nachn"/><g filter="url(#i07CAHe)"><path fill="url(#iQmQv6b)" class="ial8bmbcd"/></g><g filter="url(#irEnAvb)"><ellipse transform="rotate(-27.914 12.718 9.873)" class="d74dy-ufg"/><ellipse fill="url(#imUFlzd)" transform="rotate(-27.914 12.718 9.873)" class="yr9gap40w"/></g><g filter="url(#iDDPike)"><path fill="url(#icAVtsb)" class="n4pvl-n3b"/><path fill="url(#i6RCrab)" class="n4pvl-n3b"/><path fill="url(#iRgfRle)" class="n4pvl-n3b"/><path fill="url(#isztVdd)" class="n4pvl-n3b"/><path fill="url(#ieX1ake)" class="n4pvl-n3b"/></g><g filter="url(#iblxW1d)"><path stroke="url(#iAY17ZI)" class="tpib47b7r"/></g><g filter="url(#iky60uH)"><path stroke="url(#iBRZq6b)" class="f_dl7ccdv"/></g><g filter="url(#ijYVSIe)"><path stroke="url(#ijiEdsc)" class="e-w1rnbkk"/></g><defs><radialGradient id="irEGmjb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.026 3.96)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iDlYaab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 18.9 5.122)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="ig9vVVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -3.6875 5.80667 -2.75572 9.4 14.278)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="i0miImb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.138 16.285)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="idecHKc" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 2.995 25.247)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iFGpAuD" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.168 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="i3x6dVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 15.207 16.153)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iCzhvqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 14.353 19.551)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="icZHkOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 14.6 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="i10nBHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.128 19.652)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iUYlqpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.43272 -4.29817 0 15.816 16.575)" gradientUnits="userSpaceOnUse"><stop class="rifopebvv"/><stop offset="1" class="r8q177bio"/></radialGradient><radialGradient id="iYBCXPv" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01563 -1.90625 0 20.213 12.08)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="mwt-15bim"/><stop offset="1" class="pft2s7y0a"/><stop offset="1" class="w-5lnlbgj"/></radialGradient><radialGradient id="iNGLDge" cx="0" cy="0" r="1" gradientTransform="rotate(112.706 2.213 8.755)scale(2.34894 4.29829)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="i4eOq0b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.47656 .18752 -.03734 -.49314 11.594 10.59)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="irpe6nb" cx="0" cy="0" r="1" gradientTransform="matrix(1.43293 2.74627 -4.4155 2.30388 17.687 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i0c4J2b" cx="0" cy="0" r="1" gradientTransform="rotate(-33.074 26.893 -25.881)scale(2.07337 1.66975)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="i05ugEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -3 4.88327 1.8821 19.37 10.908)" gradientUnits="userSpaceOnUse"><stop offset=".59" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iUBpvne" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.135 11.694)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iey3g0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.148 18.81)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iR4A6ek" cx="0" cy="0" r="1" gradientTransform="rotate(171.751 8.833 6.198)scale(5.82222 8.37371)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="coa_d7btz"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iwtYXPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.94897 -10.0989 0 15.204 7.041)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="mmt32_2jk"/><stop offset="1" class="rwmq5reyz"/></radialGradient><radialGradient id="i1tbkvf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.19726 1.79589 0 17.546 9.638)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="m_h8nlt2c"/><stop offset="1" class="ry4ntn_xd"/></radialGradient><radialGradient id="it4wuUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.76145 1.42099 0 12.823 9.28)" gradientUnits="userSpaceOnUse"><stop class="jc44pgb1x"/><stop offset="1" class="x6qjx4bsp"/></radialGradient><radialGradient id="iMmrm5b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14405 3.36108 -3.07491 -1.9615 17.995 6.81)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="c5vvditnt"/><stop offset="1" class="s5u4569pn"/></radialGradient><radialGradient id="iZ3lSse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.23438 4.07813 0 14.932 17.112)" gradientUnits="userSpaceOnUse"><stop class="kvbrxgexh"/><stop offset=".608" class="i43--s3sh"/></radialGradient><radialGradient id="iRbL9Fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22684 -.76458 0 15.672 12.237)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iknWdCb" cx="0" cy="0" r="1" gradientTransform="rotate(156.852 6.695 7.47)scale(1.64873 2.52797)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i2ewT8c" cx="0" cy="0" r="1" gradientTransform="matrix(2.14063 0 0 .4039 17.588 7.075)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="h3qsa1h8x"/><stop offset="1" class="f_1ak3b9g"/></radialGradient><radialGradient id="iyTL6td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7453 1.74043 -2.1505 -2.15651 27.073 23.393)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iJEbbub" cx="0" cy="0" r="1" gradientTransform="rotate(-37.286 48.37 -27.815)scale(.99065 .51735)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iFT09oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 25.32 24.77)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="i5EFKMl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 25.344 21.59)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="iXstkgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 24.846 21.973)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="iUnKlDX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 17.421 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i6PAMSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.19 10.055)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ih2TDcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 12.994 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="imUFlzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 12.703 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6RCrab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.1 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iRgfRle" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.1 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="isztVdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.1 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ieX1ake" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.1 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><linearGradient id="iVMolOd" x1="15.128" x2="15.128" y1="4.01" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iHYvMVc" x1="15.208" x2="15.208" y1="4.809" y2="14.841" gradientUnits="userSpaceOnUse"><stop class="it3_zgbzt"/><stop offset=".888" class="ghz36ubjz"/></linearGradient><linearGradient id="iSVnEyb" x1="8.148" x2="4.557" y1="28.434" y2="28.434" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iytNNTc" x1="25.71" x2="22.168" y1="22.864" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iyfgqhc" x1="19.207" x2="18.273" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iqly9hd" x1="11.207" x2="11.541" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="igT1Aoe" x1="9.268" x2="10.424" y1="12.955" y2="12.955" gradientUnits="userSpaceOnUse"><stop offset=".127" class="lb5e6tbwl"/><stop offset="1" class="d0d035b1g"/></linearGradient><linearGradient id="iC70Uzb" x1="9.856" x2="12.977" y1="10.723" y2="10.149" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iR93tBZ" x1="21.698" x2="20.965" y1="9.982" y2="12.768" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iK87wRd" x1="20.027" x2="20.027" y1="9.427" y2="11.753" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iT1MBrd" x1="16.37" x2="15.158" y1="29.122" y2="21.997" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="io7tJwE" x1="22.221" x2="21.995" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iP2XIAc" x1="8.148" x2="8.272" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iUPlhmz" x1="12.995" x2="19.526" y1="28.341" y2="28.341" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="io5aNLb" x1="20.182" x2="15.973" y1="13.534" y2="13.29" gradientUnits="userSpaceOnUse"><stop class="hgqs6y9yl"/><stop offset=".246" class="l1w12qbms"/></linearGradient><linearGradient id="iQHyaXl" x1="16.043" x2="15.208" y1="11.6" y2="11.637" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="idXTCTh" x1="15.208" x2="15.208" y1="12.659" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iYaMVid" x1="15.208" x2="15.208" y1="9.913" y2="10.653" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iDRJLSb" x1="13.865" x2="14.218" y1="14.22" y2="13.315" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iKwHkib" x1="24.818" x2="24.818" y1="21.591" y2="24.77" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="i6Wm2kO" x1="24.846" x2="24.846" y1="22.294" y2="21.7" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="i4PraBb" x1="18.211" x2="17.892" y1="10.024" y2="10.22" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQmQv6b" x1="13.748" x2="13.43" y1="10.024" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icAVtsb" x1="26.69" x2="22.662" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iAY17ZI" x1="23.182" x2="24.891" y1="26.036" y2="26.036" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iBRZq6b" x1="23.104" x2="24.813" y1="27.341" y2="27.341" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ijiEdsc" x1="23.182" x2="24.891" y1="28.645" y2="28.645" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><filter id="i8NF4Ke" width="20.537" height="10.328" x="4.689" y="4.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1801" result="effect2_innerShadow_4002_1801"/></filter><filter id="i5lAcCc" width="8" height="6.44" x="11.207" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/></filter><filter id="iHvS7Oe" width="2.74" height="2.74" x="8.868" y="9.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".125"/></filter><filter id="iDD8Egc" width="3.327" height="3.327" x="18.364" y="8.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".25"/></filter><filter id="iQ20vOE" width="8.45" height="4.612" x="10.938" y="25.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".125"/></filter><filter id="icZLspc" width="8.05" height="4.28" x="11.088" y="25.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/></filter><filter id="iEIvJBU" width="11.119" height="10.38" x="10.02" y="6.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.156863 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1801" result="effect2_innerShadow_4002_1801"/></filter><filter id="iQ6flCe" width="3.871" height="4.695" x="13.079" y="9.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".5"/></filter><filter id="izYt6ib" width="2.271" height="3.095" x="14.072" y="9.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".1"/></filter><filter id="iHMylNc" width="3.933" height="1.672" x="13.181" y="13.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".05"/></filter><filter id="iSfgE4b" width="2.195" height="1.016" x="16.786" y="7.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/></filter><filter id="iz51mpd" width="2.095" height=".766" x="16.836" y="7.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".075"/></filter><filter id="iM4jXdd" width="2.195" height="1.016" x="11.427" y="7.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/></filter><filter id="igp4Aac" width="2.095" height=".766" x="11.477" y="7.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".075"/></filter><filter id="iqgO9dc" width="4.103" height=".85" x="15.908" y="6.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/></filter><filter id="i3JkxGe" width="7.625" height="9.853" x="21.061" y="10.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1801" result="effect2_innerShadow_4002_1801"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1801" result="effect3_innerShadow_4002_1801"/></filter><filter id="iomuude" width=".795" height=".703" x="16.678" y="9.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".05"/></filter><filter id="iJiv8ge" width=".898" height=".921" x="17.532" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".1"/></filter><filter id="i07CAHe" width=".995" height="1.05" x="13.024" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".1"/></filter><filter id="irEnAvb" width=".923" height=".712" x="12.257" y="9.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".05"/></filter><filter id="iDDPike" width="4.468" height="5.556" x="22.662" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1801"/></filter><filter id="iblxW1d" width="2.097" height=".3" x="23.032" y="25.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".05"/></filter><filter id="iky60uH" width="2.097" height=".3" x="22.954" y="27.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".05"/></filter><filter id="ijYVSIe" width="2.097" height=".3" x="23.032" y="28.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1801" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:farmer-dark" /></template>
<style>
.a23r32zth {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.635 10.535l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b4i7app5l {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.634 9.21c.662 0 1.222.457 1.374 1.074a.278.278 0 0 1-.271.346h-2.264a.233.233 0 0 1-.23-.276a1.42 1.42 0 0 1 1.39-1.144");
}

.b75_wpb8k {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.138 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c5vvditnt {
  stop-color: var(--svg-color--4c3537, #4C3537);
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.coa_d7btz {
  stop-color: var(--svg-color--523732, #523732);
}

.cvjsb-a9z {
  d: path("M17.618 7.61h2.392c-.35-.48-.922-.8-1.552-.8h-2.55c.42.5 1.05.8 1.71.8");
}

.d0d035b1g {
  stop-color: var(--svg-color--1f1b1c, #1F1B1C);
}

.d5ycxbcbt {
  d: path("m12.172 21.473l3.035-2.123l2.988 2.084c.42.325 1.012.465 1.012-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.595.823.964.563");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.d74dy-ufg {
  cx: 12.718px;
  cy: 9.873px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e-w1rnbkk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.182 28.567h1.797");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.ed1dgs27p {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.828 10.31l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.ek7xw4b6q {
  d: path("M15.138 18.67c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.f_1ak3b9g {
  stop-color: var(--svg-color--2d282a, #2D282A);
}

.f_dl7ccdv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.104 27.263h1.797");
}

.f6dcfqkjw {
  fill: var(--svg-color--000, #000);
  d: path("M16.905 10.391c0-.288.23-.518.518-.518a.516.516 0 0 1 .461.757h-.918a.47.47 0 0 1-.061-.239");
}

.fb4b6ibbm {
  d: path("M20.028 11.753a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g5-i25boa {
  d: path("M10.238 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.ghz36ubjz {
  stop-color: var(--svg-color--6e4c49, #6E4C49);
}

.guv-zxbmy {
  d: path("M25.98 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h3qsa1h8x {
  stop-color: var(--svg-color--454142, #454142);
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

.hgqs6y9yl {
  stop-color: var(--svg-color--5b4543, #5B4543);
}

.hliw7p2yd {
  fill: var(--svg-color--2a0119, #2A0119);
  d: path("M15.148 13.69c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.i43--s3sh {
  stop-color: var(--svg-color--3f3437, #3F3437);
  stop-opacity: 0;
}

.ial8bmbcd {
  d: path("M13.819 10.285c0-.293-.238-.488-.302-.547l-.293.283l.18.367z");
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.it3_zgbzt {
  stop-color: var(--svg-color--593238, #593238);
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j0mjhicuv {
  stroke: var(--svg-color--130e18, #130E18);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.732 8.278s-.625-.473-1.696-.344");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j5lippbik {
  d: path("m16.058 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.jc44pgb1x {
  stop-color: var(--svg-color--382427, #382427);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k3hh8cmzu {
  d: path("M24.084 19.989h1.524v1.734a.25.25 0 0 1-.25.25h-1.024a.25.25 0 0 1-.25-.25z");
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kbq762bbe {
  d: path("m14.828 10.31l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kchpczmzf {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.732 8.216s-.625-.473-1.696-.344");
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kvbrxgexh {
  stop-color: var(--svg-color--3f3437, #3F3437);
}

.l1w12qbms {
  stop-color: var(--svg-color--513835, #513835);
  stop-opacity: 0;
}

.lb5e6tbwl {
  stop-color: var(--svg-color--423734, #423734);
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

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m_h8nlt2c {
  stop-color: var(--svg-color--412727, #412727);
}

.m7gf2ccaq {
  d: path("M12.992 9.486a.905.905 0 0 0-.873 1.144h1.75a1 1 0 0 0 .032-.239a.91.91 0 0 0-.91-.905");
}

.m8928m_ok {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M21.963 11.044a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.602-.601");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mmt32_2jk {
  stop-color: var(--svg-color--3f2330, #3F2330);
  stop-opacity: 0;
}

.msktp5b2o {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.677 8.216s.625-.473 1.695-.344");
}

.mwmfdtbeb {
  d: path("m20.378 8.96l.01-.11c.04-1.09-.83-2.04-1.93-2.04h-6.5c-1.14 0-2.03.97-1.93 2.1l.3 4.65a3.95 3.95 0 0 0 3.92 3.43h1.9c1.98 0 3.66-1.47 3.92-3.43z");
}

.mwt-15bim {
  stop-color: var(--svg-color--3b3a3c, #3B3A3C);
}

.n4pvl-n3b {
  d: path("M22.662 25.306a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.or181q_tu {
  d: path("M20.028 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p20764brf {
  d: path("M18.628 25.81h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
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

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.qem3izvox {
  d: path("M25.32 21.77h-1v3h1z");
}

.qk4zjubee {
  d: path("M18.23 10.272a.85.85 0 0 0-.235-.47l-.263.29l.119.231z");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r416lacsv {
  d: path("M10.238 11.71a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.r8q177bio {
  stop-color: var(--svg-color--211211, #211211);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rifopebvv {
  stop-color: var(--svg-color--332022, #332022);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.rwmq5reyz {
  stop-color: var(--svg-color--29231d, #29231D);
}

.ry4ntn_xd {
  stop-color: var(--svg-color--412727, #412727);
  stop-opacity: 0;
}

.s5u4569pn {
  stop-color: var(--svg-color--4c3537, #4C3537);
  stop-opacity: 0;
}

.sbcqa9buf {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M18.628 25.81h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t0ml3mcnn {
  d: path("M22.168 29.98V18.01h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.t9ltvac_b {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.703 13.264c-.223-.119-.438.136-.308.337c.373.57 1.016.954 1.753.954s1.38-.384 1.752-.954a.23.23 0 0 0-.027-.286a.24.24 0 0 0-.279-.052l-.002.001a3.1 3.1 0 0 1-1.444.351a3.1 3.1 0 0 1-1.445-.351Z");
}

.tnmr6xw7v {
  d: path("M17.423 9.486a.906.906 0 0 1 .873 1.144h-1.75a.91.91 0 0 1 .877-1.144");
}

.tpib47b7r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.182 25.958h1.797");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.tyab5j04g {
  stroke: var(--svg-color--130e18, #130E18);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.677 8.278s.625-.473 1.695-.344");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uywde0klz {
  d: path("M17.648 10.25v5.35l1.89-.65c.88-.3 1.46-1.13 1.46-2.06v-2.53c-1.12-.04-2.24-.08-3.35-.11");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v82ve8b3o {
  d: path("M17.357 9.677c.064.086-.07.192-.224.306c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.v8kh6dbqe {
  d: path("M10.771 4.81c-.849.03-2.678.228-4.101 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.094 1.781 1.445 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.882-4.93V9.23c0-.969-.239-2.123-1.476-3.086c-1.424-1.107-3.253-1.304-4.102-1.336z");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.ven7bix4o {
  d: path("m9.278 10.19l-.01 2.69c0 .93.59 1.75 1.46 2.06l1.89.65v-5.43c-1.1 0-2.22 0-3.34.03");
}

.vptu-acpa {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.782 9.21c-.663 0-1.223.457-1.375 1.074a.278.278 0 0 0 .272.346h2.263c.144 0 .26-.132.23-.276a1.42 1.42 0 0 0-1.39-1.144");
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.w-5lnlbgj {
  stop-color: var(--svg-color--221c28, #221C28);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w29231b4u {
  d: path("M8.148 29.98V18.01H8.14a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w390nachn {
  fill: var(--svg-color--000, #000);
  d: path("M13.51 10.391a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.462.757h.918a.5.5 0 0 0 .062-.239");
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.w7k27yp0g {
  d: path("m9.308 5.55l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.x2lxohqli {
  d: path("M22.168 18.04c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x6qjx4bsp {
  stop-color: var(--svg-color--382427, #382427);
  stop-opacity: 0;
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xiqrb2bni {
  d: path("M15.138 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.ybi_ymbzs {
  d: path("M21.128 5.91h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.ye_0_ib9j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.357 9.677c.064.086-.07.192-.224.306c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.365c.154-.114.33-.137.395-.05");
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yr9gap40w {
  cx: 12.718px;
  cy: 9.873px;
  rx: 0.395px;
  ry: 0.2px;
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
