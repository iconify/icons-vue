<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibOGYLe)" class="kh-1d8bql"/><path fill="url(#icu9skl)" class="kh-1d8bql"/><path fill="url(#iX9jwpc)" class="kh-1d8bql"/><path fill="url(#iJKsOee)" class="kh-1d8bql"/><path fill="url(#ixcmlTd)" class="kh-1d8bql"/><path fill="url(#iGSJ8tc)" class="kh-1d8bql"/><path fill="url(#ioN9sMd)" class="kh-1d8bql"/><path fill="url(#i4Ewv6b)" class="x6y_meb5h"/><path fill="url(#ibOCcre)" class="x7hbu3bxv"/><path fill="url(#i2ekg6c)" class="h2d3nmh2d"/><path fill="url(#iekmmue)" class="h2d3nmh2d"/><path fill="url(#idVywLe)" class="h2d3nmh2d"/><path fill="url(#iO3Wjec)" class="glig06bzk"/><path fill="url(#iF4y3Qd)" class="glig06bzk"/><path fill="url(#iOdKbjc)" class="glig06bzk"/><path fill="url(#iBSgcUd)" class="rj76mtbcn"/><path fill="url(#idgHazw)" class="rj76mtbcn"/><path fill="url(#i4Ewv6b)" class="x6y_meb5h"/><path fill="url(#ibOCcre)" class="x7hbu3bxv"/><g filter="url(#i9gXt9d)"><path class="ekrncu4nv"/></g><g filter="url(#igPEaxb)"><path fill="url(#ikyYnbe)" class="n3a9edgqi"/></g><path fill="url(#ixSUFab)" class="e51ywwl1q"/><path fill="url(#iJacCZb)" class="e51ywwl1q"/><path fill="url(#ijYrcId)" class="e51ywwl1q"/><path fill="url(#iHYA9wd)" class="e51ywwl1q"/><path fill="url(#iLxeAPb)" class="e51ywwl1q"/><path fill="url(#i3mMBbb)" class="e51ywwl1q"/><path fill="url(#i6Iy0ry)" class="e76a0xkxe"/><path fill="url(#iATgfod)" class="e76a0xkxe"/><path fill="url(#ibZzoEe)" class="e76a0xkxe"/><path fill="url(#iu8IFcc)" class="e76a0xkxe"/><path fill="url(#iC1cl9i)" class="e76a0xkxe"/><path fill="url(#i0aPB9d)" class="e76a0xkxe"/><path fill="url(#i9Rm6lc)" class="bsppo3bns"/><path clip-rule="evenodd" class="xluf9xzjj"/><path fill="url(#iMURWFp)" clip-rule="evenodd" class="dx9pmybtq"/><path fill="url(#iTKGiCb)" clip-rule="evenodd" class="dx9pmybtq"/><path fill="url(#i1mo3Yb)" clip-rule="evenodd" class="dx9pmybtq"/><path fill="url(#iiN74Ub)" clip-rule="evenodd" class="dx9pmybtq"/><g filter="url(#ia92Rjd)"><path class="ylkdfib0r"/></g><path fill="url(#iqB0ZZo)" class="r6efnj8rg"/><g filter="url(#i7ma3Id)"><path fill="url(#iLfG2RL)" class="qo_fzqbfw"/></g><g filter="url(#iwjovvb)"><path fill="url(#ibNrjUz)" clip-rule="evenodd" class="w687xib_c"/></g><g filter="url(#iPaanSb)"><path class="rkjj6ubrf"/></g><path fill="url(#iGcqJhX)" clip-rule="evenodd" class="j8tkxyjud"/><path fill="url(#iFHWxQd)" clip-rule="evenodd" class="j8tkxyjud"/><path fill="url(#iX1j7Me)" clip-rule="evenodd" class="ecpa-eb3v"/><path fill="url(#iQzEYQc)" clip-rule="evenodd" class="ecpa-eb3v"/><path fill="url(#ijMnk8d)" class="s096nd5tv"/><path fill="url(#ioK11Vd)" class="kaf_zm66p"/><g filter="url(#is0jn8c)"><path fill="url(#iD3lMRd)" class="zgy4lcb8w"/><path fill="url(#iNpoeId)" class="zgy4lcb8w"/></g><path fill="url(#i3PD7kc)" class="zgy4lcb8w"/><path fill="url(#igrxdie)" class="zgy4lcb8w"/><path fill="url(#irBn8Me)" class="zgy4lcb8w"/><path fill="url(#iq7ECoM)" class="zgy4lcb8w"/><path fill="url(#iDyABba)" class="zgy4lcb8w"/><path fill="url(#iVD7nDk)" class="zgy4lcb8w"/><path fill="url(#icD6ked)" class="zgy4lcb8w"/><g filter="url(#iGFPNzJ)"><path class="ejm8kbcks"/></g><g filter="url(#iPanh9A)"><path class="j6_l_accg"/><path fill="url(#io9adee)" class="xwwszfbbf"/><path fill="url(#iZB0E3b)" class="xwwszfbbf"/><path fill="url(#iSm3gpe)" class="xwwszfbbf"/><path fill="url(#iaDeMfd)" class="xwwszfbbf"/><path fill="url(#is787ob)" class="xwwszfbbf"/></g><path fill="url(#iEU7Fde)" class="xwwszfbbf"/><path fill="url(#ixbqCnc)" class="xwwszfbbf"/><g filter="url(#ilQJhvz)"><path stroke="url(#ivCGQnc)" class="u1gc1kb7w"/></g><path fill="url(#i1mRYQb)" class="ibf1sn3jk"/><g filter="url(#ibZ8lfd)"><path fill="url(#i9UJYCv)" class="xymi1bc2m"/><path fill="url(#iWDe6tc)" class="xymi1bc2m"/><path fill="url(#i4dYL1d)" class="xymi1bc2m"/><path fill="url(#i8ZUMPL)" class="xymi1bc2m"/><path fill="url(#ilHRsLd)" class="xymi1bc2m"/></g><g filter="url(#i57s14b)"><path class="lyjfoh3bd"/></g><g filter="url(#ieUVIKd)"><path class="bfbntr86w"/></g><g filter="url(#iDn6iUd)"><path class="tgpj84bnk"/><path fill="url(#i4Z5Zxc)" class="vzpqhhbgs"/><path fill="url(#iFvcdja)" class="vzpqhhbgs"/></g><g filter="url(#i0iZnad)"><path class="jy0s6uble"/><path fill="url(#iKE3pmc)" class="bnoj_2dhc"/><path fill="url(#i49a4be)" class="bnoj_2dhc"/></g><path class="v5h1hnl4u"/><path fill="url(#iVw4LzZ)" class="nd1g5_bqv"/><path class="dv19ozxxx"/><g filter="url(#iO0heMc)"><path class="m3twfmbqa"/><path fill="url(#i4UuaLd)" class="j9jd-bc4x"/></g><g filter="url(#iUA58ye)"><path fill="url(#i1zRCNb)" class="k_dcfxw2l"/></g><path class="qrt_sr7jo"/><path fill="url(#iuVSG0n)" class="iey3ezbtf"/><path class="m947obc3h"/><g filter="url(#iCV8wKd)"><path fill="url(#i4P3U1W)" class="x0y_r0uxx"/></g><g filter="url(#iZVUsXb)"><ellipse transform="rotate(-27.914 13.532 9.94)" class="xr89ao__v"/><ellipse fill="url(#ibItIrc)" transform="rotate(-27.914 13.532 9.94)" class="d-qezxbvu"/></g><path fill="url(#ibFHqOf)" class="lwvz5hb3i"/><path fill="url(#iOQFble)" class="lwvz5hb3i"/><path fill="url(#iONXbMb)" class="lwvz5hb3i"/><path fill="url(#i5thAsb)" class="lwvz5hb3i"/><path fill="url(#iXK4xOk)" class="l65ax5bsv"/><path fill="url(#irl21Le)" class="l65ax5bsv"/><g filter="url(#iX24Mfd)"><path fill="url(#iScrqgI)" class="mqwb2cbcm"/></g><g filter="url(#iQoOEke)"><path fill="url(#irtVZfb)" class="ex_p_st_g"/></g><g filter="url(#iBVcGmd)"><path class="f2pqlbovm"/></g><g filter="url(#iT8q4gc)"><path class="y6p6j8b2z"/></g><g filter="url(#ixT7gCc)"><path class="wsb_5j1bg"/></g><defs><radialGradient id="ibOGYLe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.18 23.934)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="ixcmlTd" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.15 8.188)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iGSJ8tc" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.338 23.555)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="ioN9sMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.951 30.003)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="i2ekg6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.317 24.715)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iekmmue" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.722 12.33)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iO3Wjec" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.216 21.965)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iF4y3Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.529 20.34)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="iBSgcUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 15.985 18.559)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="xmwtowbdl"/><stop offset="1" class="g0ldwhbeh"/><stop offset="1" class="g0ldwhbeh"/></radialGradient><radialGradient id="idgHazw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.349 30.496)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="ukvvntb_q"/><stop offset="1" class="z549t7awi"/></radialGradient><radialGradient id="iHYA9wd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.124 18.122)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iLxeAPb" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.431 26.564)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="i3mMBbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.124 24.872)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="i6Iy0ry" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.372 11.28)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="iATgfod" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.115 24.926)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iu8IFcc" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.286 19.497)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iC1cl9i" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.083 18.325)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="i0aPB9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.82812 2.125 -.73855 .63537 12.427 21.34)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="i9Rm6lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.84375 3.36136 0 15.97 18.95)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="wqp-dxinn"/><stop offset=".857" class="gsl3hsbhe"/></radialGradient><radialGradient id="iTKGiCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.49 16.387)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="euff42j2w"/><stop offset="1" class="u6die0o1z"/></radialGradient><radialGradient id="i1mo3Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.567 20.043)" gradientUnits="userSpaceOnUse"><stop class="l7pwaz3tj"/><stop offset="1" class="knxty7b6k"/></radialGradient><radialGradient id="iiN74Ub" cx="0" cy="0" r="1" gradientTransform="rotate(116.378 1.745 12.244)scale(2.14524 1.11803)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="mfg518bmg"/><stop offset="1" class="jgi1fkzwi"/></radialGradient><radialGradient id="iqB0ZZo" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.145 18.064)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iLfG2RL" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.233 25.91)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="iFHWxQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.115 23.575)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="ijMnk8d" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.822 20.85)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="ioK11Vd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 9.928 12.383)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iD3lMRd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.793 10.952)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iNpoeId" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.522 8.178)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="igrxdie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27297 7.3692 0 15.967 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="irBn8Me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.432 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iq7ECoM" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.703 -2.024)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iDyABba" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.418 11.94)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iVD7nDk" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.193 8.22)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="icD6ked" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.107 13.818)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iZB0E3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.451 12.312)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iaDeMfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.567 11.743)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ixbqCnc" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.915 9.015)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="i1mRYQb" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.494 14.575)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iWDe6tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.755 8.06)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i4dYL1d" cx="0" cy="0" r="1" gradientTransform="matrix(.11404 -2.51254 4.45174 .20206 20.846 9.37)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i8ZUMPL" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.091 3.093)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ilHRsLd" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.08 1.501)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="i4Z5Zxc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.238 3.76)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iFvcdja" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.265 -5.723)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iKE3pmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.619 7.574)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="i49a4be" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.733 6.098)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iVw4LzZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.167 10.036)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i4UuaLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.939 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuVSG0n" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.803 10.036)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibItIrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.517 10.255)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOQFble" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.603 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iONXbMb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.963 10.594)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i5thAsb" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.077 10.767)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="irl21Le" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.07 10.69)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iScrqgI" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.071 10.693)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="icu9skl" x1="23.294" x2="22.982" y1="24.613" y2="24.614" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iX9jwpc" x1="8.716" x2="9.052" y1="24.614" y2="24.613" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iJKsOee" x1="16.161" x2="16.161" y1="30.965" y2="29.153" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="i4Ewv6b" x1="8.8" x2="23.176" y1="15.442" y2="15.442" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ibOCcre" x1="8.8" x2="23.176" y1="15.412" y2="15.412" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="idVywLe" x1="6.98" x2="6.98" y1="30.778" y2="29.318" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iOdKbjc" x1="22.651" x2="23.43" y1="25.652" y2="25.652" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ikyYnbe" x1="16.161" x2="23.786" y1="26.997" y2="19.403" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="ixSUFab" x1="21.875" x2="16.76" y1="18.392" y2="23.91" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iJacCZb" x1="20.029" x2="19.872" y1="15.673" y2="17.736" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="ijYrcId" x1="17.567" x2="18.724" y1="18.918" y2="19.403" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="ibZzoEe" x1="12.255" x2="12.583" y1="23.215" y2="22.856" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iMURWFp" x1="20.294" x2="19.622" y1="23.684" y2="23.7" gradientUnits="userSpaceOnUse"><stop offset=".294" class="u1y0uumqm"/><stop offset="1" class="j-esh3bss"/></linearGradient><linearGradient id="ibNrjUz" x1="12.19" x2="12.19" y1="20.294" y2="28.465" gradientUnits="userSpaceOnUse"><stop class="ubba03gja"/><stop offset="1" class="e_s6vnbxu"/></linearGradient><linearGradient id="iGcqJhX" x1="9.499" x2="10.393" y1="25.282" y2="25.282" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iX1j7Me" x1="13.872" x2="14.544" y1="25.292" y2="25.292" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iQzEYQc" x1="14.935" x2="14.692" y1="24.809" y2="24.809" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="i3PD7kc" x1="21.142" x2="18.613" y1="12.637" y2="12.637" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="io9adee" x1="16.823" x2="15.985" y1="11.627" y2="11.661" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iSm3gpe" x1="15.985" x2="15.985" y1="12.766" y2="12.301" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="is787ob" x1="15.985" x2="15.985" y1="10.061" y2="10.607" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iEU7Fde" x1="16.401" x2="16.401" y1="12.903" y2="12.711" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="ivCGQnc" x1="14.783" x2="15.102" y1="14.337" y2="13.502" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="i9UJYCv" x1="22.837" x2="11.225" y1="5.289" y2="5.289" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="i1zRCNb" x1="18.945" x2="18.631" y1="10.09" y2="10.283" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4P3U1W" x1="14.547" x2="14.233" y1="10.09" y2="10.283" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibFHqOf" x1="22.421" x2="21.215" y1="10.117" y2="12.293" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iXK4xOk" x1="10.135" x2="11.594" y1="10.82" y2="10.693" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="irtVZfb" x1="21.401" x2="21.401" y1="9.735" y2="11.638" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="i9gXt9d" width="7.147" height="11.557" x="9.015" y="15.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".5"/></filter><filter id="igPEaxb" width="7.147" height="11.557" x="15.909" y="15.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".5"/></filter><filter id="ia92Rjd" width="3.699" height="3.699" x="16.98" y="24.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".375"/></filter><filter id="i7ma3Id" width="1.42" height="1.42" x="18.95" y="24.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/></filter><filter id="iwjovvb" width="5.381" height="7.171" x="9.499" y="19.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/></filter><filter id="iPaanSb" width="5.3" height="6.89" x="9.565" y="19.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".15"/></filter><filter id="is0jn8c" width="11.22" height="12.542" x="10.922" y="4.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24147" result="effect2_innerShadow_3987_24147"/></filter><filter id="iGFPNzJ" width="3.747" height="4.9" x="13.97" y="9.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".5"/></filter><filter id="iPanh9A" width="2.277" height="3.3" x="14.846" y="9.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".1"/></filter><filter id="ilQJhvz" width="3.718" height="1.573" x="14.126" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".05"/></filter><filter id="ibZ8lfd" width="12.873" height="8.356" x="9.549" y="1.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24147" result="effect2_innerShadow_3987_24147"/></filter><filter id="i57s14b" width="2.339" height="1.19" x="17.574" y="7.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/></filter><filter id="ieUVIKd" width="2.339" height="1.176" x="12.318" y="7.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/></filter><filter id="iDn6iUd" width="6.584" height="5.992" x="9.904" y="2.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24147"/><feGaussianBlur result="effect2_foregroundBlur_3987_24147" stdDeviation=".125"/></filter><filter id="i0iZnad" width="6.319" height="5.711" x="15.826" y="3.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".125"/></filter><filter id="iO0heMc" width=".787" height=".696" x="17.433" y="9.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".05"/></filter><filter id="iUA58ye" width=".891" height=".913" x="18.273" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".1"/></filter><filter id="iCV8wKd" width=".986" height="1.04" x="13.83" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".1"/></filter><filter id="iZVUsXb" width=".913" height=".704" x="13.075" y="9.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".05"/></filter><filter id="iX24Mfd" width="1.329" height="2.379" x="9.904" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".125"/></filter><filter id="iQoOEke" width="1.947" height="2.903" x="20.428" y="9.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".25"/></filter><filter id="iBVcGmd" width="2.405" height="1.16" x="12.237" y="7.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".125"/></filter><filter id="iT8q4gc" width="2.405" height="1.16" x="17.516" y="7.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".125"/></filter><filter id="ixT7gCc" width="5.266" height="3.005" x="16.864" y="3.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24147" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:health-worker-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bfbntr86w {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.574 7.863a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.bnoj_2dhc {
  d: path("m21.198 8.603l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.135-.12-.368c-.256-.97.672-1.706 1.65-1.488c.94.209 2.004.559 2.816 1.088c1.744 1.138 1.53 3.12.613 4.085");
}

.bsppo3bns {
  d: path("M15.97 18.723a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d-qezxbvu {
  cx: 13.532px;
  cy: 9.94px;
  rx: 0.39px;
  ry: 0.197px;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dv19ozxxx {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.451c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dx9pmybtq {
  fill-rule: evenodd;
  d: path("M15.92 15.123a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e_s6vnbxu {
  stop-color: var(--svg-color--5f5280, #5F5280);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e51ywwl1q {
  d: path("M16.634 21.694c-.262.516-.262.941-.262 1.306v2.99c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.058a.25.25 0 0 0-.113-.187a10.5 10.5 0 0 0-2.426-1.134a.3.3 0 0 0-.04.08z");
}

.e76a0xkxe {
  d: path("M15.355 21.694c.262.516.262.941.262 1.306v2.99c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.189-.25l.188-2.058a.25.25 0 0 1 .113-.187a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ecpa-eb3v {
  fill-rule: evenodd;
  d: path("M14.88 23.733v2.47c0 .36-.29.65-.65.65h-.58v-.98h.25v-2.14z");
}

.ejm8kbcks {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.584 10.433l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.383.484-.756l-.494-1.838c-.106-.407-.505-.407-.616 0");
}

.ekrncu4nv {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.192 20.157l.732.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .01.297l4.505 4.598c.111.112.306.038.306-.12v-3.329c0-.037-.01-.065-.018-.102l-2.54-5.887a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.002a.214.214 0 0 0 .176.232");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.euff42j2w {
  stop-color: var(--svg-color--322450, #322450);
}

.ex_p_st_g {
  d: path("M20.928 11.638q.058-.951.11-1.903a.956.956 0 0 1-.11 1.903");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f2pqlbovm {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.612 8.143c.257-.184.897-.509 1.655-.381");
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g0ldwhbeh {
  stop-color: var(--svg-color--943104, #943104);
}

.glig06bzk {
  d: path("M26.811 27.973c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.gsl3hsbhe {
  stop-color: var(--svg-color--461f1a, #461F1A);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h2d3nmh2d {
  d: path("m5.91 22.773l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibf1sn3jk {
  d: path("M15.985 13.849c-.508 0-.985-.12-1.385-.329c-.137-.07-.285.085-.198.21c.335.507.918.845 1.583.845s1.248-.338 1.583-.846c.087-.13-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iey3ezbtf {
  d: path("M13.8 9.559a.893.893 0 0 0-.86 1.127h1.725a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j-esh3bss {
  stop-color: var(--svg-color--786d95, #786D95);
  stop-opacity: 0;
}

.j6_l_accg {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.603 10.237l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.j8tkxyjud {
  fill-rule: evenodd;
  d: path("M9.5 26.193v-2.47h.98v2.14h.25v.98h-.58a.65.65 0 0 1-.65-.65");
}

.j9jd-bc4x {
  d: path("M18.104 9.747c.063.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jgi1fkzwi {
  stop-color: var(--svg-color--2c1f4a, #2C1F4A);
  stop-opacity: 0;
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jy0s6uble {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.198 8.603l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.135-.12-.368c-.256-.97.672-1.706 1.65-1.488c.94.209 2.004.559 2.816 1.088c1.744 1.138 1.53 3.12.613 4.085");
}

.k_dcfxw2l {
  d: path("M18.964 10.334a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kaf_zm66p {
  d: path("M11.124 12.202a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.kh-1d8bql {
  d: path("M15.971 15.413c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.knxty7b6k {
  stop-color: var(--svg-color--655c80, #655C80);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l65ax5bsv {
  d: path("M10.94 9.088a1.62 1.62 0 0 0-1.391 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7pwaz3tj {
  stop-color: var(--svg-color--655c80, #655C80);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lwvz5hb3i {
  d: path("M20.907 12.293q.101-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.19");
}

.lyjfoh3bd {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.718 7.972a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m3twfmbqa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.747c.063.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.m947obc3h {
  fill: var(--svg-color--000, #000);
  d: path("M14.312 10.451a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfg518bmg {
  stop-color: var(--svg-color--2c1f4a, #2C1F4A);
}

.mqwb2cbcm {
  d: path("M10.9 9.753a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.084-1.88");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n3a9edgqi {
  d: path("m21.878 20.157l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.297l-4.505 4.598c-.112.112-.306.038-.306-.12v-3.329c0-.037.009-.065.018-.102l2.54-5.887a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.002a.214.214 0 0 1-.177.232");
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nd1g5_bqv {
  d: path("M18.17 9.559a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.qo_fzqbfw {
  d: path("M19.66 26.183a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.qrt_sr7jo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 9.287c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r6efnj8rg {
  d: path("M19.66 26.733a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rj76mtbcn {
  d: path("M16.478 22.517c0-.04-.01-.203 0-.243l2.662-6.291c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.361c.01.03.054.05.054.09l.056 3.599h.01v3.97h.79v-3.97l.078-3.416z");
}

.rkjj6ubrf {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.175 26.296h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.s096nd5tv {
  d: path("M20.846 12.202c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.02q.256-.547.346-1.18z");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
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

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tgpj84bnk {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.217 5.336l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.u1gc1kb7w {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.634 13.454a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.u1y0uumqm {
  stop-color: var(--svg-color--786d95, #786D95);
}

.u6die0o1z {
  stop-color: var(--svg-color--322450, #322450);
  stop-opacity: 0;
}

.ubba03gja {
  stop-color: var(--svg-color--554975, #554975);
}

.ukvvntb_q {
  stop-color: var(--svg-color--e05a26, #E05A26);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v5h1hnl4u {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.376 9.287c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.vzpqhhbgs {
  d: path("m16.217 5.336l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.071.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w687xib_c {
  fill-rule: evenodd;
  d: path("M12.19 20.864c-.94 0-1.71.761-1.71 1.709v3.3h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 1 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wqp-dxinn {
  stop-color: var(--svg-color--633c3a, #633C3A);
}

.wsb_5j1bg {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.178 5.292h-2.081a.483.483 0 1 1 .077-.961c.54.086 1.257.206 1.737.325c1.086.269 1.385.797 1.47 1.174a1.51 1.51 0 0 0-1.203-.538");
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.x0y_r0uxx {
  d: path("M14.616 10.346c0-.288-.234-.48-.298-.538l-.288.278l.178.362z");
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x6y_meb5h {
  d: path("M16.34 15.413c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.x7hbu3bxv {
  d: path("M16.01 15.413h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xluf9xzjj {
  fill: var(--svg-color--534675, #534675);
  fill-rule: evenodd;
  d: path("M15.92 15.123a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.xmwtowbdl {
  stop-color: var(--svg-color--d76b26, #D76B26);
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xr89ao__v {
  cx: 13.532px;
  cy: 9.94px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xwwszfbbf {
  d: path("m15.603 10.237l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.xymi1bc2m {
  d: path("M20.84 4.309c.514.177.976.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.35 2.35 0 0 1 1.299-1.127a2.68 2.68 0 0 0 1.384-1.11a2.326 2.326 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y6p6j8b2z {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.546 8.097c-.257-.185-.898-.509-1.655-.382");
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.ylkdfib0r {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.83 26.962a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z549t7awi {
  stop-color: var(--svg-color--e05a26, #E05A26);
  stop-opacity: 0;
}

.zgy4lcb8w {
  d: path("M11.16 13.717a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.433h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
