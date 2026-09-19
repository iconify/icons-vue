<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#inQtY8E)" class="bm-9-rczp"/><path fill="url(#iwaY9kd)" class="bm-9-rczp"/><path fill="url(#i5e3gIe)" class="bm-9-rczp"/><path fill="url(#iWE3e2d)" class="z8sq24g1p"/><path fill="url(#iI9wnpc)" class="z8sq24g1p"/><path fill="url(#izJjDIc)" class="z8sq24g1p"/><path fill="url(#iQcpBEi)" class="z8sq24g1p"/><path fill="url(#iOVOVhd)" class="jmoky6kxu"/><path fill="url(#i3aiOgc)" class="jmoky6kxu"/><g filter="url(#iOXhU7b)"><path fill="url(#iS8H6Yc)" class="zdgf7w4yb"/><path fill="url(#iLhng6d)" class="zdgf7w4yb"/><path fill="url(#ic9e57b)" class="zdgf7w4yb"/></g><path fill="url(#iaUcPVb)" class="s9b708s1a"/><path fill="url(#iJ7aBnj)" class="lnre5rota"/><path fill="url(#ib2R3fl)" class="lnre5rota"/><path fill="url(#ii8d2qb)" class="ptimty_tl"/><path fill="url(#iP1TEdd)" class="ptimty_tl"/><path fill="url(#iJXNONt)" class="e6r7seqxp"/><path fill="url(#iA8wUyb)" class="e6r7seqxp"/><path fill="url(#iDQt7De)" class="e6r7seqxp"/><path fill="url(#idBTZzd)" class="e6r7seqxp"/><path fill="url(#ihNSLjb)" class="e6r7seqxp"/><path fill="url(#iRZjqib)" class="uy-17xzlb"/><path fill="url(#iZFJD1c)" class="uy-17xzlb"/><path fill="url(#icHM3ic)" class="uy-17xzlb"/><path fill="url(#irdI47G)" class="uy-17xzlb"/><path fill="url(#iSYAEHd)" class="pkmi_v8fq"/><path fill="url(#iadvEse)" class="pkmi_v8fq"/><path fill="url(#iWrns6d)" class="pkmi_v8fq"/><path fill="url(#iTaALVb)" class="zol_j5bxi"/><path fill="url(#i1Kgaab)" class="zol_j5bxi"/><g filter="url(#iHSj5vd)"><path fill="url(#iJ3F5dM)" class="zd8tk-bcb"/><path fill="url(#isPsyld)" class="zd8tk-bcb"/><path fill="url(#iIvVQgd)" class="zd8tk-bcb"/><path fill="url(#ih0Uyyd)" class="zd8tk-bcb"/><path fill="url(#iVfe8Zb)" class="zd8tk-bcb"/></g><rect fill="url(#ioG7C2c)" class="szqn253sx"/><rect fill="url(#ieX6SFe)" class="szqn253sx"/><g filter="url(#iacO0Zd)"><path fill="url(#ic2ygye)" class="rhp53ibxf"/></g><g filter="url(#iNLkf6c)"><path fill="url(#i5G9R1d)" class="od62z7brh"/></g><g filter="url(#iuwjNae)"><path fill="url(#ipWf6je)" class="bagpgjbpl"/></g><g filter="url(#ieLxIPc)"><path stroke="url(#iogHvVc)" class="vz04i31ke"/></g><g filter="url(#iqcSX2c)"><path stroke="url(#i0Gscsd)" class="q20uyubtf"/></g><g filter="url(#imowImb)"><path stroke="url(#i4LpKLw)" class="ghw1j7b6b"/></g><path fill="url(#i7o3DYc)" class="kidxlr4rn"/><path fill="url(#ikZFs5R)" class="esjgj-bgm"/><g filter="url(#itrXxqe)"><path fill="url(#iRiJMMb)" class="d_edsac4c"/></g><path fill="url(#ip0a3rc)" class="d_edsac4c"/><path fill="url(#i5SF8De)" class="d_edsac4c"/><path fill="url(#iPODVgd)" class="d_edsac4c"/><path fill="url(#iIjt07b)" class="d_edsac4c"/><path fill="url(#i8hUwnA)" class="d_edsac4c"/><path fill="url(#ic2eVJG)" class="d_edsac4c"/><path fill="url(#iktKiYb)" class="d_edsac4c"/><g filter="url(#i957Uve)"><path class="b0p_h9bww"/></g><g filter="url(#ipbgHGb)"><path class="zfl6u4bzv"/><path fill="url(#iuixVgc)" class="girr56bnt"/><path fill="url(#imMZxAK)" class="girr56bnt"/><path fill="url(#iCO4Oxd)" class="girr56bnt"/><path fill="url(#ibNTY6c)" class="girr56bnt"/><path fill="url(#iczo5Mc)" class="girr56bnt"/></g><g filter="url(#in9uztd)"><path stroke="url(#iVMXvdd)" class="f2nzzov2o"/></g><path fill="url(#iorooGb)" class="bqdkyvbya"/><g filter="url(#ixuhPWb)"><path fill="url(#ixu85fe)" class="wqd3xxbph"/><path fill="url(#iUH4Ere)" class="wqd3xxbph"/><path fill="url(#iJzIZWO)" class="wqd3xxbph"/><path fill="url(#iDYpONb)" class="wqd3xxbph"/><path fill="url(#iYQp5Ed)" class="wqd3xxbph"/></g><g filter="url(#ifYt6gb)"><path class="n88ef1zie"/></g><g filter="url(#iMXI3Tc)"><path class="ylf3llk1h"/></g><g filter="url(#iBr4Ffc)"><path class="ea06mabru"/><path fill="url(#iBeZ8xc)" class="pz8nag2wq"/><path fill="url(#iVboaMd)" class="pz8nag2wq"/></g><g filter="url(#iyQYZYb)"><path class="gxhwsobaf"/><path fill="url(#iVmNZxb)" class="ofos7dbso"/><path fill="url(#iU6K6ib)" class="ofos7dbso"/><path fill="url(#idhY4Pe)" class="ofos7dbso"/></g><path class="t94bz3bde"/><path fill="url(#iuYIoMc)" class="i5fyz5r8l"/><path class="pwz01_19y"/><g filter="url(#ilkxPLc)"><path class="silzzb4ef"/><path fill="url(#iEbeACb)" class="a94pmrneq"/></g><g filter="url(#iAuFdQb)"><path fill="url(#iXgoJDd)" class="okqefvurr"/></g><path class="gyqnirb9l"/><path fill="url(#i3MqcXd)" class="nv9k21-0z"/><path class="ezqadhbww"/><g filter="url(#isCmzZb)"><path fill="url(#i3mYu5c)" class="dm5ry5jqy"/></g><g filter="url(#igMqwud)"><ellipse transform="rotate(-27.914 13.703 10.39)" class="b5v7_1bhi"/><ellipse fill="url(#ie7S5Pc)" transform="rotate(-27.914 13.703 10.39)" class="ksmynubew"/></g><path fill="url(#ixELtxc)" class="l2mkskbko"/><path fill="url(#iiop8Wd)" class="l2mkskbko"/><path fill="url(#icOydRb)" class="l2mkskbko"/><path fill="url(#ig2VGHb)" class="l2mkskbko"/><path fill="url(#if9hZ2p)" class="stt8rac0z"/><path fill="url(#ihw2ehd)" class="stt8rac0z"/><g filter="url(#i9i8Ote)"><path fill="url(#i3kC02c)" class="zp9ux0bbg"/></g><g filter="url(#iTDdhOe)"><path fill="url(#i374wyb)" class="haweqhb3w"/></g><g filter="url(#iBPWQOc)"><path class="mun3ylqzb"/></g><g filter="url(#iZt8Bjc)"><path class="ubyip01zz"/></g><defs><radialGradient id="iWE3e2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.085 29.996)" gradientUnits="userSpaceOnUse"><stop class="ogfz3obbf"/><stop offset=".434" class="odeeueq9k"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iI9wnpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.933 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="izJjDIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.933 23.047)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iOVOVhd" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.09 4.505)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="i3aiOgc" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.215 23.15)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iLhng6d" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.175 14.808)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="ic9e57b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.175 16.386)" gradientUnits="userSpaceOnUse"><stop class="o-r-orbbu"/><stop offset="1" class="smcyj7aql"/></radialGradient><radialGradient id="iaUcPVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.163 18.496)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="iJ7aBnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -1.38289 0 16.936 16.458)" gradientUnits="userSpaceOnUse"><stop class="ka05cbbzq"/><stop offset="1" class="gvm18n_ss"/></radialGradient><radialGradient id="ib2R3fl" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.165 15.37)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="d-ldk52ts"/><stop offset=".957" class="kps9w0cij"/></radialGradient><radialGradient id="ii8d2qb" cx="0" cy="0" r="1" gradientTransform="rotate(154.355 11.505 15.158)scale(2.33554 2.29591)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iP1TEdd" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.44 -29.212)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iDQt7De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.86 17.389)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="irdI47G" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.574 17.215)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iWrns6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.34 17.465)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iTaALVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.261 24.28)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="isPsyld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.03 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iIvVQgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.03 26.595)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ih0Uyyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.03 27.845)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iVfe8Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.03 29.197)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ioG7C2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.707 21.457)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="i7o3DYc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.584 21.198)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="ikZFs5R" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 10.1 12.833)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iRiJMMb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.964 11.402)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="i5SF8De" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0253 -10.7865 0 16.74 5.23)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="dfy4z6b7v"/><stop offset=".973" class="c76oh-f-x"/></radialGradient><radialGradient id="iPODVgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.603 10.089)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iIjt07b" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.856 10.135)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="i8hUwnA" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.589 12.39)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="ic2eVJG" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 10.688 7.076)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iktKiYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.583 6.423)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="imMZxAK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.622 12.762)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="ibNTY6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.738 12.193)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iorooGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 16.156 14.941)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iUH4Ere" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.926 8.51)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iJzIZWO" cx="0" cy="0" r="1" gradientTransform="matrix(.11404 -2.51254 4.45173 .20206 21.017 9.82)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iDYpONb" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.662 -1.261)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iYQp5Ed" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09581 15.25 1.951)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iBeZ8xc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 16.41 4.21)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iVboaMd" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 10.725 8.153)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iVmNZxb" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 19.57 4.987)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iU6K6ib" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.79 8.024)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="idhY4Pe" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -47.26 156.97)scale(3.27032 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iuYIoMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.338 10.485)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iEbeACb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.643 .85)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3MqcXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.974 10.485)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ie7S5Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.687 10.705)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiop8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.773 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="icOydRb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.134 11.044)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="ig2VGHb" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.248 11.216)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="ihw2ehd" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.96 5.23)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="i3kC02c" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 11.241 11.142)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><linearGradient id="inQtY8E" x1="16.162" x2="16.162" y1="15.537" y2="30.421" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="iwaY9kd" x1="23.59" x2="21.058" y1="26.59" y2="26.621" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="i5e3gIe" x1="8.617" x2="10.833" y1="26.405" y2="26.405" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iQcpBEi" x1="9.081" x2="8.646" y1="28.062" y2="28.062" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iS8H6Yc" x1="22.902" x2="17.027" y1="18.496" y2="18.496" gradientUnits="userSpaceOnUse"><stop class="b-744zb0c"/><stop offset="1" class="jz3pzrmrk"/></linearGradient><linearGradient id="iJXNONt" x1="27.902" x2="24.527" y1="20.715" y2="20.34" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="iA8wUyb" x1="25.622" x2="25.622" y1="20.98" y2="20.465" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="idBTZzd" x1="25.622" x2="25.622" y1="16.835" y2="17.465" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="ihNSLjb" x1="23.325" x2="24.067" y1="19.182" y2="19.182" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iRZjqib" x1="23.496" x2="22.199" y1="18.966" y2="18.966" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iZFJD1c" x1="23.746" x2="23.355" y1="19.246" y2="19.246" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="icHM3ic" x1="22.95" x2="22.95" y1="21.076" y2="20.414" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="iSYAEHd" x1="29.197" x2="27.577" y1="19.413" y2="19.413" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iadvEse" x1="28.496" x2="28.496" y1="21.051" y2="20.527" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="i1Kgaab" x1="25.624" x2="25.652" y1="21.992" y2="22.348" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iJ3F5dM" x1="27.621" x2="23.593" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="ieX6SFe" x1="25.634" x2="25.634" y1="20.808" y2="21.269" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="ic2ygye" x1="17.212" x2="17.212" y1="29.599" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="i5G9R1d" x1="13.205" x2="13.205" y1="29.599" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ipWf6je" x1="21.199" x2="21.199" y1="29.599" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iogHvVc" x1="24.113" x2="25.822" y1="26.066" y2="26.066" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i0Gscsd" x1="24.035" x2="25.744" y1="27.371" y2="27.371" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i4LpKLw" x1="24.113" x2="25.822" y1="28.675" y2="28.675" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ip0a3rc" x1="21.313" x2="16.96" y1="13.087" y2="13.087" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iuixVgc" x1="16.994" x2="16.156" y1="12.076" y2="12.111" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iCO4Oxd" x1="16.156" x2="16.156" y1="13.216" y2="12.751" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iczo5Mc" x1="16.156" x2="16.156" y1="10.382" y2="11.057" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iVMXvdd" x1="14.954" x2="15.272" y1="14.787" y2="13.952" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="ixu85fe" x1="23.008" x2="11.396" y1="5.739" y2="5.739" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iXgoJDd" x1="19.116" x2="18.802" y1="10.539" y2="10.733" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3mYu5c" x1="14.718" x2="14.404" y1="10.539" y2="10.733" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixELtxc" x1="22.592" x2="21.385" y1="10.566" y2="12.743" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="if9hZ2p" x1="10.306" x2="11.764" y1="11.27" y2="11.143" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="i374wyb" x1="21.635" x2="21.635" y1="10.195" y2="12.098" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><filter id="iOXhU7b" width="14.254" height="7.618" x="9.149" y="15.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1740" result="effect2_innerShadow_4002_1740"/></filter><filter id="iHSj5vd" width="4.468" height="5.556" x="23.593" y="24.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/></filter><filter id="iacO0Zd" width="1.192" height="6.826" x="15.579" y="23.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="iNLkf6c" width="1.192" height="6.826" x="11.573" y="23.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="iuwjNae" width="1.192" height="6.826" x="19.566" y="23.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="ieLxIPc" width="2.097" height=".3" x="23.963" y="25.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".05"/></filter><filter id="iqcSX2c" width="2.097" height=".3" x="23.885" y="27.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".05"/></filter><filter id="imowImb" width="2.097" height=".3" x="23.963" y="28.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".05"/></filter><filter id="itrXxqe" width="11.22" height="12.542" x="11.093" y="5.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1740" result="effect2_innerShadow_4002_1740"/></filter><filter id="i957Uve" width="3.747" height="4.9" x="14.14" y="9.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".5"/></filter><filter id="ipbgHGb" width="2.277" height="3.3" x="15.017" y="10.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".1"/></filter><filter id="in9uztd" width="3.718" height="1.573" x="14.296" y="13.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".05"/></filter><filter id="ixuhPWb" width="12.873" height="8.356" x="9.719" y="2.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1740" result="effect2_innerShadow_4002_1740"/></filter><filter id="ifYt6gb" width="2.339" height="1.19" x="17.745" y="7.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/></filter><filter id="iMXI3Tc" width="2.339" height="1.176" x="12.489" y="7.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/></filter><filter id="iBr4Ffc" width="6.734" height="5.992" x="10.075" y="3.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1740"/><feGaussianBlur result="effect2_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="iyQYZYb" width="6.361" height="5.736" x="15.997" y="3.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="ilkxPLc" width=".787" height=".696" x="17.604" y="10.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".05"/></filter><filter id="iAuFdQb" width=".891" height=".913" x="18.444" y="10.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".1"/></filter><filter id="isCmzZb" width=".986" height="1.04" x="14.001" y="10.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".1"/></filter><filter id="igMqwud" width=".913" height=".705" x="13.246" y="10.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".05"/></filter><filter id="i9i8Ote" width="1.329" height="2.379" x="10.075" y="9.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="iTDdhOe" width="1.947" height="2.903" x="20.662" y="9.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".25"/></filter><filter id="iBPWQOc" width="2.405" height="1.16" x="12.408" y="7.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter><filter id="iZt8Bjc" width="2.405" height="1.16" x="17.687" y="7.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1740" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:judge-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a94pmrneq {
  d: path("M18.274 10.197c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.158-.358s.326-.136.39-.051");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
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

.b0p_h9bww {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.754 10.878l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.408-.505-.408-.616 0");
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b5v7_1bhi {
  cx: 13.703px;
  cy: 10.39px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.bagpgjbpl {
  d: path("M19.816 23.54h.692v6.326h-.692z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bm-9-rczp {
  d: path("M16.165 15.537c-6.114 0-11.08 4.906-11.08 10.969v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.955-10.97-11.07-10.97");
}

.bqdkyvbya {
  d: path("M16.156 14.298c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.085-.198.209c.335.508.919.846 1.584.846s1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c76oh-f-x {
  stop-color: var(--svg-color--ae7a81, #AE7A81);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d_edsac4c {
  d: path("M11.331 14.167a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.d-ldk52ts {
  stop-color: var(--svg-color--94624b, #94624B);
  stop-opacity: 0;
}

.dfy4z6b7v {
  stop-color: var(--svg-color--d49c9b, #D49C9B);
  stop-opacity: 0;
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dm5ry5jqy {
  d: path("M14.787 10.796c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
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

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e6r7seqxp {
  d: path("M27.073 16.951h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h2.9a.505.505 0 0 0 .505-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.ea06mabru {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.388 5.786l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.893v1.485z");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.esjgj-bgm {
  d: path("M11.295 12.652a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.ezqadhbww {
  fill: var(--svg-color--000, #000);
  d: path("M14.483 10.9a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.f2nzzov2o {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.805 13.903a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ghw1j7b6b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 28.597h1.797");
}

.girr56bnt {
  d: path("m15.774 10.687l-.532 1.838c-.109.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gvm18n_ss {
  stop-color: var(--svg-color--c49384, #C49384);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gxhwsobaf {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.368 9.053l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.67-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.744 1.137 1.439 3.188.52 4.154");
}

.gyqnirb9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.765 9.737c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.haweqhb3w {
  d: path("M21.162 12.098q.057-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i5fyz5r8l {
  d: path("M18.34 10.008a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jmoky6kxu {
  d: path("M23.388 29.996v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jz3pzrmrk {
  stop-color: var(--svg-color--3e3646, #3E3646);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.ka05cbbzq {
  stop-color: var(--svg-color--b98383, #B98383);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kidxlr4rn {
  d: path("M21.017 12.652c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kps9w0cij {
  stop-color: var(--svg-color--94624b, #94624B);
}

.ksmynubew {
  cx: 13.703px;
  cy: 10.39px;
  rx: 0.39px;
  ry: 0.197px;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2mkskbko {
  d: path("M21.078 12.743c.065-1.065.129-2.127.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnre5rota {
  d: path("M16.165 18.73a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.927 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.065");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mun3ylqzb {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.783 8.593c.257-.185.897-.51 1.655-.382");
}

.n88ef1zie {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.889 8.422a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.213-.057a.277.277 0 0 0 .068.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 1 0 .364-.418");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nv9k21-0z {
  d: path("M13.972 10.008a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o-r-orbbu {
  stop-color: var(--svg-color--1c1124, #1C1124);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
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

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od62z7brh {
  d: path("M11.823 23.54h.692v6.326h-.692z");
}

.odeeueq9k {
  stop-color: var(--svg-color--675375, #675375);
}

.ofos7dbso {
  d: path("m21.368 9.053l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.67-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.744 1.137 1.439 3.188.52 4.154");
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ogfz3obbf {
  stop-color: var(--svg-color--957b8d, #957B8D);
}

.okqefvurr {
  d: path("M19.135 10.783a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkmi_v8fq {
  d: path("M28.694 16.951h-.614a.505.505 0 0 0-.503.504v3.022c0 .272.221.503.503.503h.614a.505.505 0 0 0 .503-.503v-3.022a.51.51 0 0 0-.503-.504");
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.ptimty_tl {
  d: path("M26.949 22.929c.531 0 .959.427.959.959v2.188H26v-2.188a.94.94 0 0 1 .948-.959");
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pwz01_19y {
  fill: var(--svg-color--000, #000);
  d: path("M17.829 10.9c0-.283.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pz8nag2wq {
  d: path("m16.388 5.786l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.893v1.485z");
}

.q20uyubtf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.035 27.293h1.797");
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rhp53ibxf {
  d: path("M15.829 23.54h.692v6.326h-.692z");
}

.s9b708s1a {
  d: path("m16.956 19.879l.136-.122a3.5 3.5 0 0 0 1.148-2.548v-1.964h-4.15l-.005 1.911c0 .052.003.147 0 .2c.045.916.46 1.784 1.144 2.401l.16.143l.666-1.009a.13.13 0 0 1 .22 0z");
}

.silzzb4ef {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.274 10.197c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.158-.358s.326-.136.39-.051");
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.smcyj7aql {
  stop-color: var(--svg-color--1c1124, #1C1124);
  stop-opacity: 0;
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.stt8rac0z {
  d: path("M11.111 9.542a1.62 1.62 0 0 0-1.392 1.594c0 .86.674 1.561 1.521 1.607a78 78 0 0 1-.129-3.2");
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.szqn253sx {
  width: 2.773px;
  height: 1.082px;
  x: 24.247px;
  y: 20.98px;
  rx: 0.541px;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t94bz3bde {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.547 9.737c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ubyip01zz {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.717 8.546c-.257-.184-.898-.508-1.655-.38");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uy-17xzlb {
  d: path("M23.168 16.951h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vz04i31ke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.113 25.988h1.797");
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wqd3xxbph {
  d: path("M21.01 4.759a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526c-.175.258-.27.564-.27.875v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.843 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ylf3llk1h {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.745 8.313a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z8sq24g1p {
  d: path("M8.933 29.996v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zd8tk-bcb {
  d: path("M23.593 25.322a.73.73 0 0 1 .726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.zdgf7w4yb {
  d: path("M9.236 17.864c1.974-1.646 4.386-2.423 6.94-2.423c2.553 0 4.965.777 6.939 2.423a.24.24 0 0 1 .061.296c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.296");
}

.zfl6u4bzv {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.774 10.687l-.532 1.838c-.109.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zol_j5bxi {
  d: path("M24.869 21.067v6.427h1.51v-6.427z");
}

.zp9ux0bbg {
  d: path("M11.07 10.203a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
