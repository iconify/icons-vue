<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5Oca6c)" class="alxybhl0b"/><path fill="url(#i3g6qdc)" class="alxybhl0b"/><path fill="url(#irzC14b)" class="alxybhl0b"/><path fill="url(#ibeoXPb)" class="rxud36bii"/><path fill="url(#iHSLUdN)" class="rxud36bii"/><path fill="url(#ibasGWb)" class="rxud36bii"/><path fill="url(#igN1nUB)" class="rxud36bii"/><path fill="url(#iApV6Ph)" class="qf6dr7l0s"/><path fill="url(#ipO8iNe)" class="qf6dr7l0s"/><g filter="url(#ijfrcOe)"><path fill="url(#ivGpmHe)" class="t0ywo4bta"/><path fill="url(#iySVxie)" class="t0ywo4bta"/><path fill="url(#i5xejWd)" class="t0ywo4bta"/></g><path fill="url(#iYCzW8c)" class="cutvs1bzx"/><path fill="url(#i55Cpde)" class="m793rbcrp"/><path fill="url(#iANuy0R)" class="fpkpek4da"/><path fill="url(#iNhKBJe)" class="fpkpek4da"/><path fill="url(#ihVkUyd)" class="t7os6va_e"/><path fill="url(#iZuPbwb)" class="t7os6va_e"/><path fill="url(#iGGY54x)" class="vmz8mwbdx"/><path fill="url(#ibOlsib)" class="vmz8mwbdx"/><path fill="url(#iJM8Hjb)" class="vmz8mwbdx"/><path fill="url(#iUdLtTp)" class="vmz8mwbdx"/><path fill="url(#iSeU0fd)" class="vmz8mwbdx"/><path fill="url(#iQWJwTd)" class="vmhl_zbpr"/><path fill="url(#iUnvzBd)" class="vmhl_zbpr"/><path fill="url(#iTdbN0b)" class="vmhl_zbpr"/><path fill="url(#i7zCtpe)" class="vmhl_zbpr"/><path fill="url(#iGASolb)" class="srj3yxb8c"/><path fill="url(#inZWrBe)" class="srj3yxb8c"/><path fill="url(#iLOVIIb)" class="srj3yxb8c"/><path fill="url(#itBO9Qb)" class="fgop05-bu"/><path fill="url(#iCCEgGc)" class="fgop05-bu"/><g filter="url(#ipljvZb)"><path fill="url(#iRRlrte)" class="orge31bys"/><path fill="url(#irvx6Lb)" class="orge31bys"/><path fill="url(#ierKNge)" class="orge31bys"/><path fill="url(#i12cfxe)" class="orge31bys"/><path fill="url(#iyb6ysb)" class="orge31bys"/></g><rect fill="url(#iUX14dL)" class="fgy89acrf"/><rect fill="url(#iBoco5d)" class="fgy89acrf"/><g filter="url(#ibxGLSb)"><path fill="url(#iAlU59b)" class="xkswqsbgz"/></g><g filter="url(#ivHLEzd)"><path fill="url(#isnOqIb)" class="h2d9p3fjb"/></g><g filter="url(#iQXnJyc)"><path fill="url(#iPuU0Ub)" class="n08z7bbmh"/></g><g filter="url(#iaXuatb)"><path stroke="url(#iNQz4Cd)" class="p-x4l9bzr"/></g><g filter="url(#iUqQ3dd)"><path stroke="url(#iyNBmBe)" class="u4kbq9b0g"/></g><g filter="url(#iSO8nFb)"><path stroke="url(#ir8ZMzc)" class="piec55b2u"/></g><path fill="url(#iNRPgGR)" class="obz3f9bpt"/><path fill="url(#im9Hf2Y)" class="j0rek5ilb"/><g filter="url(#ivHJ6jc)"><path fill="url(#iiFxOJc)" class="i3d0v55ye"/><path fill="url(#iltXOGb)" class="i3d0v55ye"/></g><path fill="url(#iw4d0bT)" class="i3d0v55ye"/><path fill="url(#ihsFBnd)" class="i3d0v55ye"/><path fill="url(#i9DS1ye)" class="i3d0v55ye"/><path fill="url(#is3rLzb)" class="i3d0v55ye"/><path fill="url(#iGYohYI)" class="i3d0v55ye"/><path fill="url(#iH46aqb)" class="i3d0v55ye"/><path fill="url(#inf1GGc)" class="i3d0v55ye"/><g filter="url(#ioJtm3k)"><path class="x9nkx2bvs"/></g><g filter="url(#ilwHO5q)"><path class="wwh1ocbnx"/><path fill="url(#ipqRHde)" class="qdvg4pbkc"/><path fill="url(#iGO9bKc)" class="qdvg4pbkc"/><path fill="url(#iX6l7ib)" class="qdvg4pbkc"/><path fill="url(#ibAjdRq)" class="qdvg4pbkc"/><path fill="url(#iQcToXd)" class="qdvg4pbkc"/></g><path fill="url(#icsmAgM)" class="qdvg4pbkc"/><path fill="url(#i2TsSke)" class="qdvg4pbkc"/><g filter="url(#iwmgaGX)"><path stroke="url(#iGnoOYb)" class="j7enlwb-v"/></g><path fill="url(#iORK5Le)" class="zfqd4q2ns"/><g filter="url(#iygJ8Zz)"><path fill="url(#ih66c5h)" class="z-ebsz01s"/><path fill="url(#iPcJ5Ae)" class="z-ebsz01s"/><path fill="url(#i0w3SDh)" class="z-ebsz01s"/><path fill="url(#i85Ckjc)" class="z-ebsz01s"/><path fill="url(#iXDeVzd)" class="z-ebsz01s"/></g><g filter="url(#iF0a0LZ)"><path class="vt6fvsd4n"/></g><g filter="url(#iN4e07c)"><path class="w7pirmbyv"/></g><g filter="url(#iEE6Ggb)"><path class="zhwxebbmx"/><path fill="url(#iXbCCMb)" class="p35wtd2da"/><path fill="url(#iQMNDpb)" class="p35wtd2da"/></g><g filter="url(#iIXNVqI)"><path class="xxaq-u_pt"/><path fill="url(#i6taY1b)" class="k5zwwvbmp"/><path fill="url(#i3zREXc)" class="k5zwwvbmp"/></g><path class="kqcr68bdj"/><path fill="url(#i5EzSVw)" class="dwg5j1b-r"/><path class="tuklzv7to"/><g filter="url(#ieNowHc)"><path class="j61czrb4f"/><path fill="url(#iJPkmgd)" class="fsm3w5oxv"/></g><g filter="url(#iWH3Zwc)"><path fill="url(#iFWTc9b)" class="q9u57jf4m"/></g><path class="jufy023un"/><path fill="url(#iTO9d0b)" class="ygvb9irub"/><path class="jx7rhfdxb"/><g filter="url(#ibC8rrd)"><path fill="url(#iPNFUvd)" class="jn45-kejj"/></g><g filter="url(#in6Zckr)"><ellipse transform="rotate(-27.914 13.702 9.825)" class="ie6q0hozy"/><ellipse fill="url(#ibjJdce)" transform="rotate(-27.914 13.702 9.825)" class="zrbedbbpm"/></g><path fill="url(#ie6oBxd)" class="xx47onbuh"/><path fill="url(#iOmWZdd)" class="xx47onbuh"/><path fill="url(#ioj95Pd)" class="xx47onbuh"/><path fill="url(#ixQ17pd)" class="xx47onbuh"/><path fill="url(#iNadmle)" class="a8m_ejbze"/><path fill="url(#iTrKcOm)" class="a8m_ejbze"/><g filter="url(#iFASvge)"><path fill="url(#ifNixSb)" class="fk0r8abwy"/></g><g filter="url(#iiYlUab)"><path fill="url(#iX9F8ne)" class="zrgnehbzm"/></g><g filter="url(#idboyld)"><path class="z38f25brf"/></g><g filter="url(#iBsxFrw)"><path class="z9fns6bum"/></g><g filter="url(#i4qwxLd)"><path class="ut9rkjlsu"/></g><defs><radialGradient id="ibeoXPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.085 29.956)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iHSLUdN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.933 29.956)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ibasGWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.933 23.007)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iApV6Ph" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.074 4.485)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ipO8iNe" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.215 23.11)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iySVxie" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.175 14.768)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="i5xejWd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.175 16.346)" gradientUnits="userSpaceOnUse"><stop class="o-r-orbbu"/><stop offset="1" class="smcyj7aql"/></radialGradient><radialGradient id="i55Cpde" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.163 18.456)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="iANuy0R" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -1.38289 0 16.936 16.419)" gradientUnits="userSpaceOnUse"><stop class="rcw9-ibyp"/><stop offset="1" class="a0wobz7cx"/></radialGradient><radialGradient id="iNhKBJe" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.165 15.33)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="qtyvlkbuk"/><stop offset="1" class="gicq3c6bu"/></radialGradient><radialGradient id="ihVkUyd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57562 1.29893 -1.2769 -1.54888 27.908 23.516)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="iZuPbwb" cx="0" cy="0" r="1" gradientTransform="matrix(.75156 -.57402 .30002 .3928 27.675 23.365)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iJM8Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.86 17.349)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="i7zCtpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.574 17.175)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iLOVIIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.34 17.425)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="itBO9Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.261 24.24)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="irvx6Lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.03 25.26)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ierKNge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.03 26.555)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i12cfxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.03 27.805)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iyb6ysb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.03 29.157)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iUX14dL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.707 21.417)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="iNRPgGR" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.99 20.915)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="im9Hf2Y" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 10.1 12.268)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iiFxOJc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.963 10.837)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iltXOGb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.64 8.169)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="ihsFBnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27297 7.3692 0 16.138 17.227)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="i9DS1ye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.603 9.524)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="is3rLzb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.73 -2.167)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iGYohYI" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.588 11.825)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iH46aqb" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.364 8.104)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="inf1GGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23466 2.49744 -.99833 -.0938 21.7 7.92)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iGO9bKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.622 12.197)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="ibAjdRq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.738 11.628)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="i2TsSke" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 6.023 8.992)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="iORK5Le" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.665 14.46)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iPcJ5Ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.926 7.945)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i0w3SDh" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.35 -6.369)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i85Ckjc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.262 2.978)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iXDeVzd" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.25 1.386)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iXbCCMb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.41 3.645)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iQMNDpb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.246 -5.935)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i6taY1b" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.79 7.46)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="i3zREXc" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.903 5.983)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i5EzSVw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.338 9.92)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iJPkmgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.11 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTO9d0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.974 9.92)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibjJdce" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.687 10.14)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOmWZdd" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.774 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ioj95Pd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.134 10.48)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ixQ17pd" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.248 10.652)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iTrKcOm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.24 10.576)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ifNixSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.241 10.578)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="i5Oca6c" x1="16.162" x2="16.162" y1="15.497" y2="30.381" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="i3g6qdc" x1="23.59" x2="21.058" y1="26.55" y2="26.581" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="irzC14b" x1="8.617" x2="10.833" y1="26.365" y2="26.365" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="igN1nUB" x1="9.081" x2="8.646" y1="28.022" y2="28.022" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ivGpmHe" x1="22.902" x2="17.027" y1="18.456" y2="18.456" gradientUnits="userSpaceOnUse"><stop class="b-744zb0c"/><stop offset="1" class="jz3pzrmrk"/></linearGradient><linearGradient id="iYCzW8c" x1="17.293" x2="15.996" y1="19.034" y2="19.956" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="iGGY54x" x1="27.902" x2="24.527" y1="20.675" y2="20.3" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="ibOlsib" x1="25.622" x2="25.622" y1="20.94" y2="20.425" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iUdLtTp" x1="25.622" x2="25.622" y1="16.795" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iSeU0fd" x1="23.325" x2="24.067" y1="19.142" y2="19.142" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iQWJwTd" x1="23.496" x2="22.199" y1="18.926" y2="18.926" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iUnvzBd" x1="23.746" x2="23.355" y1="19.206" y2="19.206" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iTdbN0b" x1="22.95" x2="22.95" y1="21.037" y2="20.374" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="iGASolb" x1="29.197" x2="27.577" y1="19.373" y2="19.373" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="inZWrBe" x1="28.496" x2="28.496" y1="21.011" y2="20.487" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iCCEgGc" x1="25.624" x2="25.652" y1="21.952" y2="22.308" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iRRlrte" x1="27.621" x2="23.593" y1="28.019" y2="28.019" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iBoco5d" x1="25.634" x2="25.634" y1="20.769" y2="21.23" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iAlU59b" x1="17.212" x2="17.212" y1="29.559" y2="22.883" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="isnOqIb" x1="13.205" x2="13.205" y1="29.559" y2="22.883" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iPuU0Ub" x1="21.199" x2="21.199" y1="29.559" y2="22.883" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iNQz4Cd" x1="24.113" x2="25.822" y1="26.026" y2="26.026" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iyNBmBe" x1="24.035" x2="25.744" y1="27.331" y2="27.331" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ir8ZMzc" x1="24.113" x2="25.822" y1="28.636" y2="28.636" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iw4d0bT" x1="21.313" x2="18.784" y1="12.522" y2="12.522" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ipqRHde" x1="16.994" x2="16.156" y1="11.512" y2="11.546" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iX6l7ib" x1="16.156" x2="16.156" y1="12.651" y2="12.186" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iQcToXd" x1="16.156" x2="16.156" y1="9.946" y2="10.492" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="icsmAgM" x1="16.571" x2="16.571" y1="12.789" y2="12.596" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iGnoOYb" x1="14.954" x2="15.272" y1="14.222" y2="13.387" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ih66c5h" x1="23.008" x2="11.396" y1="5.174" y2="5.174" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iFWTc9b" x1="19.116" x2="18.802" y1="9.975" y2="10.168" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPNFUvd" x1="14.718" x2="14.404" y1="9.974" y2="10.168" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ie6oBxd" x1="22.592" x2="21.385" y1="10.001" y2="12.178" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iNadmle" x1="10.306" x2="11.764" y1="10.706" y2="10.578" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iX9F8ne" x1="21.572" x2="21.572" y1="9.62" y2="11.523" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="ijfrcOe" width="14.254" height="7.618" x="9.149" y="15.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1731" result="effect2_innerShadow_4002_1731"/></filter><filter id="ipljvZb" width="4.468" height="5.556" x="23.593" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/></filter><filter id="ibxGLSb" width="1.192" height="6.826" x="15.579" y="23.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="ivHLEzd" width="1.192" height="6.826" x="11.573" y="23.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="iQXnJyc" width="1.192" height="6.826" x="19.566" y="23.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="iaXuatb" width="2.097" height=".3" x="23.963" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".05"/></filter><filter id="iUqQ3dd" width="2.097" height=".3" x="23.885" y="27.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".05"/></filter><filter id="iSO8nFb" width="2.097" height=".3" x="23.963" y="28.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".05"/></filter><filter id="ivHJ6jc" width="11.22" height="12.542" x="11.092" y="4.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1731" result="effect2_innerShadow_4002_1731"/></filter><filter id="ioJtm3k" width="3.747" height="4.9" x="14.14" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".5"/></filter><filter id="ilwHO5q" width="2.277" height="3.3" x="15.017" y="9.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".1"/></filter><filter id="iwmgaGX" width="3.718" height="1.573" x="14.296" y="13.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".05"/></filter><filter id="iygJ8Zz" width="12.873" height="8.356" x="9.719" y="1.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1731" result="effect2_innerShadow_4002_1731"/></filter><filter id="iF0a0LZ" width="2.339" height="1.19" x="17.745" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/></filter><filter id="iN4e07c" width="2.339" height="1.176" x="12.489" y="7.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/></filter><filter id="iEE6Ggb" width="6.584" height="5.992" x="10.075" y="2.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1731"/><feGaussianBlur result="effect2_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="iIXNVqI" width="6.319" height="5.711" x="15.997" y="3.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="ieNowHc" width=".787" height=".696" x="17.604" y="9.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".05"/></filter><filter id="iWH3Zwc" width=".891" height=".913" x="18.444" y="9.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".1"/></filter><filter id="ibC8rrd" width=".986" height="1.04" x="14.001" y="9.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".1"/></filter><filter id="in6Zckr" width=".913" height=".705" x="13.246" y="9.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".05"/></filter><filter id="iFASvge" width="1.329" height="2.379" x="10.075" y="9.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="iiYlUab" width="1.947" height="2.903" x="20.599" y="9.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".25"/></filter><filter id="idboyld" width="2.305" height="1.06" x="12.458" y="7.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="iBsxFrw" width="2.305" height="1.06" x="17.736" y="7.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".125"/></filter><filter id="i4qwxLd" width="5.266" height="3.005" x="17.035" y="3.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1731" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:judge-medium-dark" /></template>
<style>
.a0wobz7cx {
  stop-color: var(--svg-color--664543, #664543);
}

.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a8m_ejbze {
  d: path("M11.112 8.973a1.62 1.62 0 0 0-1.393 1.598c0 .86.674 1.561 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.alxybhl0b {
  d: path("M16.165 15.497c-6.114 0-11.08 4.906-11.08 10.969v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.955-10.97-11.07-10.97");
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b-744zb0c {
  stop-color: var(--svg-color--4a4251, #4A4251);
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cutvs1bzx {
  d: path("m17.092 19.717l-.654.585a.416.416 0 0 1-.555 0l-.654-.585a3.47 3.47 0 0 1-1.149-2.568v-3.113a2.085 2.085 0 0 1 2.086-2.065c1.148 0 2.075.927 2.075 2.075v3.113a3.5 3.5 0 0 1-1.149 2.558");
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dwg5j1b-r {
  d: path("M18.34 9.444a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fgop05-bu {
  d: path("M24.869 21.027v6.426h1.51v-6.426z");
}

.fgy89acrf {
  width: 2.773px;
  height: 1.082px;
  x: 24.247px;
  y: 20.94px;
  rx: 0.541px;
}

.fk0r8abwy {
  d: path("M11.07 9.638a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fpkpek4da {
  d: path("M16.165 18.69a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.927 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.065");
}

.fsm3w5oxv {
  d: path("M18.274 9.632c.064.085-.069.189-.22.302s-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gicq3c6bu {
  stop-color: var(--svg-color--4b2620, #4B2620);
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h2d9p3fjb {
  d: path("M11.823 23.5h.692v6.326h-.692z");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.i3d0v55ye {
  d: path("M11.33 13.602a3.916 3.916 0 0 0 3.887 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ie6q0hozy {
  cx: 13.702px;
  cy: 9.825px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.j0rek5ilb {
  d: path("M11.294 12.087a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j61czrb4f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.274 9.632c.064.085-.069.189-.22.302s-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.j7enlwb-v {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.805 13.338a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.529.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32c-.496 0-.961-.116-1.351-.32Z");
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jn45-kejj {
  d: path("M14.787 10.231c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jufy023un {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.765 9.172c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.jx7rhfdxb {
  fill: var(--svg-color--000, #000);
  d: path("M14.483 10.336a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jz3pzrmrk {
  stop-color: var(--svg-color--3e3646, #3E3646);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k5zwwvbmp {
  d: path("m21.368 8.488l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.671-1.706 1.65-1.488c.94.209 2.004.559 2.815 1.088c1.745 1.138 1.532 3.12.613 4.085");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kqcr68bdj {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.547 9.172c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.127");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m793rbcrp {
  d: path("m16.956 19.839l.136-.122a3.5 3.5 0 0 0 1.148-2.548v-1.964h-4.15l-.005 1.911c0 .052.003.147 0 .2c.045.916.46 1.784 1.144 2.401l.16.143l.666-1.009a.13.13 0 0 1 .22 0z");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n08z7bbmh {
  d: path("M19.816 23.5h.692v6.326h-.692z");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.o-r-orbbu {
  stop-color: var(--svg-color--1c1124, #1C1124);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.obz3f9bpt {
  d: path("M21.017 12.087c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.orge31bys {
  d: path("M23.593 25.282a.73.73 0 0 1 .726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592A.731.731 0 0 1 24 28.567a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p-x4l9bzr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 25.948h1.797");
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p35wtd2da {
  d: path("m16.388 5.221l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.piec55b2u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 28.558h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q9u57jf4m {
  d: path("M19.135 10.219a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.qdvg4pbkc {
  d: path("m15.773 10.122l-.531 1.838c-.109.379.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.qf6dr7l0s {
  d: path("M23.388 29.956v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qtyvlkbuk {
  stop-color: var(--svg-color--4b2620, #4B2620);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rcw9-ibyp {
  stop-color: var(--svg-color--673a48, #673A48);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rxud36bii {
  d: path("M8.933 29.956v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.smcyj7aql {
  stop-color: var(--svg-color--1c1124, #1C1124);
  stop-opacity: 0;
}

.srj3yxb8c {
  d: path("M28.694 16.911h-.614a.505.505 0 0 0-.503.504v3.022c0 .272.221.503.503.503h.614a.505.505 0 0 0 .503-.503v-3.022a.51.51 0 0 0-.503-.504");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t0ywo4bta {
  d: path("M9.236 17.824c1.974-1.646 4.386-2.423 6.94-2.423c2.553 0 4.965.777 6.939 2.423a.24.24 0 0 1 .061.296c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.296");
}

.t7os6va_e {
  d: path("M26.949 22.889c.531 0 .959.427.959.959v2.188H26v-2.188a.94.94 0 0 1 .948-.96");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tuklzv7to {
  fill: var(--svg-color--000, #000);
  d: path("M17.829 10.336c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u4kbq9b0g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.035 27.253h1.797");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ut9rkjlsu {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.349 5.177h-2.081a.483.483 0 1 1 .077-.961c.54.086 1.257.205 1.737.325c1.085.269 1.385.797 1.469 1.174a1.51 1.51 0 0 0-1.202-.538");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vmhl_zbpr {
  d: path("M23.168 16.911h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.vmz8mwbdx {
  d: path("M27.073 16.911h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h2.901a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.vt6fvsd4n {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.889 7.857a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 0 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w7pirmbyv {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.745 7.748a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wwh1ocbnx {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.773 10.122l-.531 1.838c-.109.379.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x9nkx2bvs {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.754 10.318l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.495-1.838c-.105-.407-.504-.407-.615 0");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xkswqsbgz {
  d: path("M15.829 23.5h.692v6.326h-.692z");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xx47onbuh {
  d: path("M21.078 12.178q.1-1.597.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.xxaq-u_pt {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.368 8.488l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.671-1.706 1.65-1.488c.94.209 2.004.559 2.815 1.088c1.745 1.138 1.532 3.12.613 4.085");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.ygvb9irub {
  d: path("M13.972 9.444a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z-ebsz01s {
  d: path("M21.01 4.194a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526c-.175.258-.27.564-.27.875v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.35 2.35 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.187.912-.187c.843 0 1.58.455 1.99 1.131c.307.51.79.88 1.352 1.073");
}

.z38f25brf {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.783 8.028c.257-.185.897-.51 1.655-.382");
}

.z9fns6bum {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.717 7.982c-.257-.185-.898-.509-1.655-.382");
}

.zfqd4q2ns {
  d: path("M16.156 13.733c-.508 0-.985-.119-1.386-.328c-.137-.07-.284.085-.198.209c.335.507.919.846 1.584.846s1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21c-.4.21-.873.33-1.385.33");
}

.zhwxebbmx {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.388 5.221l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zrbedbbpm {
  cx: 13.702px;
  cy: 9.825px;
  rx: 0.39px;
  ry: 0.197px;
}

.zrgnehbzm {
  d: path("M21.099 11.523q.057-.952.11-1.903a.955.955 0 0 1-.11 1.903");
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
