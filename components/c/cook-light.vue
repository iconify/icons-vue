<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i8LR0Pd)" class="cho0wwbxj"/><path fill="url(#iqNi5re)" class="h63qsw72a"/><path class="cbnipmb4g"/><path fill="url(#iwLXINj)" class="c3pazcc9s"/><path fill="url(#iclDghK)" class="rxhgcccxt"/><path fill="url(#i4rfE9d)" class="rxhgcccxt"/><path fill="url(#inP0Oyd)" class="hgez_ckwa"/><path fill="url(#ijJ9Suc)" class="hgez_ckwa"/><path fill="url(#iuNJ7qb)" class="hgez_ckwa"/><path fill="url(#i93V1pS)" class="hgez_ckwa"/><g filter="url(#iPokwdd)"><path fill="url(#i74k5kd)" class="t6pr07xmi"/><path fill="url(#iQiOQqb)" class="t6pr07xmi"/></g><path fill="url(#itqF3Vd)" class="t6pr07xmi"/><path fill="url(#i8IFnqb)" class="t6pr07xmi"/><g filter="url(#ic3nR3b)"><path fill="url(#ioTXyId)" class="kxtk97b-s"/></g><path fill="url(#iZO70ib)" class="x5m_r-40z"/><path fill="url(#iOjEvCI)" class="x5m_r-40z"/><g filter="url(#iamwKMc)"><path class="jvaz6dbql"/></g><g filter="url(#ihHtPxc)"><path class="yitm6bbcf"/></g><g filter="url(#ikZLETb)"><path class="grfxoxf1b"/></g><g filter="url(#ixiOxgM)"><path fill="url(#iu0EE4d)" class="vhcq0yb2g"/></g><g filter="url(#iZLh1sl)"><path fill="url(#iYvtXXn)" class="zxda46ott"/></g><g filter="url(#igcu2oc)"><path fill="url(#iI41UMM)" class="mvu-d8qbf"/></g><path fill="url(#izjQSrd)" class="h5wfhsdxa"/><path fill="url(#iOoHgtc)" class="h5wfhsdxa"/><path fill="url(#iSWvlAe)" class="cma9xwb_i"/><path fill="url(#iyrYLme)" class="v5ycnsq6q"/><g filter="url(#iGLi7Rd)"><path fill="url(#iYTRjQc)" class="i1din9b9j"/></g><path fill="url(#i4cj08b)" class="i1din9b9j"/><path fill="url(#iRcfkGd)" class="i1din9b9j"/><path fill="url(#iigNn7i)" class="i1din9b9j"/><path fill="url(#iOIMuZy)" class="i1din9b9j"/><path fill="url(#iYYZixc)" class="i1din9b9j"/><path fill="url(#iiJmfnb)" class="i1din9b9j"/><path fill="url(#ig2gjBb)" class="i1din9b9j"/><g filter="url(#iIW0HNd)"><path class="cu07-zbpq"/></g><g filter="url(#iO8Y7OS)"><path class="qwvc_obpa"/><path fill="url(#iFwyLLo)" class="xc5vz2nwi"/><path fill="url(#iGlhPFe)" class="xc5vz2nwi"/><path fill="url(#i5wRUhb)" class="xc5vz2nwi"/><path fill="url(#irEUhTb)" class="xc5vz2nwi"/><path fill="url(#ihDQkVb)" class="xc5vz2nwi"/></g><g filter="url(#ilRo2sd)"><path stroke="url(#ifBJf6c)" class="eth6kt59r"/></g><path fill="url(#iSqgBxb)" class="mpl2hj91k"/><g filter="url(#iWkxxcH)"><path class="n9mbalbjx"/></g><g filter="url(#inhwmTI)"><path class="nx5hvxbaz"/></g><path class="e6gu6dbjq"/><path fill="url(#ioBcoFw)" class="f0lc8cb-l"/><path class="m_titrr7w"/><g filter="url(#ihtY4ce)"><path class="c7uaskqvv"/><path fill="url(#i8poolb)" class="l1ijt7pks"/></g><g filter="url(#iJYGa9d)"><path fill="url(#iOdp95c)" class="juxik1ilm"/></g><path class="jxxebtbrj"/><path fill="url(#ii5uzUd)" class="mnnhslsrw"/><path class="p8_zej1gv"/><g filter="url(#iPSWifb)"><path fill="url(#iryQq3Q)" class="mzk447emc"/></g><g filter="url(#inRLc0b)"><ellipse transform="rotate(-27.914 13.193 9.875)" class="cm6t0pbhv"/><ellipse fill="url(#io0ua0x)" transform="rotate(-27.914 13.193 9.875)" class="ob7bcwbug"/></g><path fill="url(#ihIaqQd)" class="iwxs3cf0k"/><path fill="url(#ivYeSjc)" class="iwxs3cf0k"/><path fill="url(#iwX4uIb)" class="iwxs3cf0k"/><path fill="url(#iHNWoEe)" class="iwxs3cf0k"/><path fill="url(#iHylZPe)" class="tvis7hbtj"/><path fill="url(#i55ZT3c)" class="tvis7hbtj"/><g filter="url(#iwwSUHb)"><path fill="url(#iUTRkjd)" class="wxh3co6vs"/></g><g filter="url(#ifpsBsb)"><path fill="url(#iML575d)" class="pawfg2lic"/></g><g filter="url(#ig7dTwH)"><path class="g37mewbhm"/></g><g filter="url(#imKymca)"><path class="xqmi19bsb"/></g><g filter="url(#iZ4zRzd)"><path fill="url(#iSfaohe)" class="sq5xszbgd"/><path fill="url(#ipRkMCd)" class="sq5xszbgd"/><path fill="url(#ijZRdpb)" class="sq5xszbgd"/></g><path fill="url(#iEfaG0b)" class="rokvf6b0z"/><path fill="url(#idrl29d)" class="rokvf6b0z"/><g filter="url(#i8q7XZm)"><path fill="url(#i7dHb5c)" clip-rule="evenodd" class="izufo8bpf"/></g><g filter="url(#iXOSoJb)"><path fill="url(#i6pT3RP)" clip-rule="evenodd" class="cdwb3bbdw"/></g><g filter="url(#i6791Fd)"><path fill="url(#igCFrRd)" class="m22si5bvo"/></g><path fill="url(#iviZ2td)" class="ej8z3qyin"/><path fill="url(#iZ28Hob)" class="ej8z3qyin"/><path fill="url(#iSwgMHe)" class="ej8z3qyin"/><path fill="url(#iN9IxAg)" class="z69a7kb1f"/><path fill="url(#iDpui5Q)" class="z69a7kb1f"/><path fill="url(#iPZUYwe)" class="z69a7kb1f"/><path fill="url(#iX54eKd)" class="z69a7kb1f"/><g filter="url(#iCo9d5c)"><path fill="url(#i6NqMhe)" class="u892n_fxl"/></g><g filter="url(#iSVBUAe)"><path class="enli_kbua"/><path fill="url(#iJzqndO)" class="jioigf_uc"/></g><g filter="url(#iQsyOre)"><ellipse fill="url(#ip93O9c)" class="e1zowv8mu"/></g><g filter="url(#ibivcid)"><path fill="url(#idQbWuc)" class="qzno1cccr"/><path fill="url(#iJXmFGj)" class="qzno1cccr"/><path fill="url(#ic0DIjd)" class="qzno1cccr"/><path fill="url(#iuA41je)" class="qzno1cccr"/><path fill="url(#iYb2AEc)" class="qzno1cccr"/></g><g filter="url(#iuErZKk)"><path stroke="url(#iw5CDNb)" class="f4rh3ucjs"/></g><g filter="url(#igoEA1c)"><path stroke="url(#i16u2Bb)" class="jvsy5c46p"/></g><g filter="url(#iXgCzuc)"><path stroke="url(#iKacdXb)" class="k4hskrbnq"/></g><defs><radialGradient id="iwLXINj" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.742 57.516)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="i4rfE9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.684 30.21)" gradientUnits="userSpaceOnUse"><stop class="kz1-kyj0l"/><stop offset="1" class="d9a-s9bqe"/></radialGradient><radialGradient id="iuNJ7qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.125 30.713)" gradientUnits="userSpaceOnUse"><stop class="tb19eccqx"/><stop offset="1" class="b3_m6tbiu"/></radialGradient><radialGradient id="i93V1pS" cx="0" cy="0" r="1" gradientTransform="matrix(-4.94559 0 0 -18.6532 9.212 29.424)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="blny5fbqc"/><stop offset="1" class="ql78zhb7e"/></radialGradient><radialGradient id="i74k5kd" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.726 19.685)" gradientUnits="userSpaceOnUse"><stop class="m6lhrcc1m"/><stop offset="1" class="hm5-ozbqx"/></radialGradient><radialGradient id="iQiOQqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.39 32.457)" gradientUnits="userSpaceOnUse"><stop class="fg0e2bc1h"/><stop offset="1" class="qk3h5tshn"/></radialGradient><radialGradient id="itqF3Vd" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.505 16.03)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iZO70ib" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 8.994 10.11)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iOjEvCI" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.602 8.621)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="fjyr3161v"/><stop offset="1" class="vuu318b4c"/></radialGradient><radialGradient id="izjQSrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13534 1.02198 -1.00268 -2.09502 28.159 23.99)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iOoHgtc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.386 23.545)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iSWvlAe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.7 20.574)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iyrYLme" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.59 12.318)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iYTRjQc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26686 0 0 -9.24801 18.479 10.887)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iRcfkGd" cx="0" cy="0" r="1" gradientTransform="scale(11.1574 13.3745)rotate(90 .584 .9)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="c22lxt0bf"/><stop offset="1" class="ws083288l"/></radialGradient><radialGradient id="iigNn7i" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.43169 0 18.115 9.574)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iOIMuZy" cx="0" cy="0" r="1" gradientTransform="matrix(.00395 -1.09427 1.19972 .00433 13.332 9.62)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iYYZixc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.55937 .53641 -1.36019 -21.70422 19.108 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iiJmfnb" cx="0" cy="0" r="1" gradientTransform="matrix(3.1215 -3.27779 1.20037 1.14313 10.141 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ig2gjBb" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.388 8.036)scale(3.37573 2.79652)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iGlhPFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.113 12.247)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="irEUhTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.23 11.678)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iSqgBxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.647 14.426)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ioBcoFw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.829 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8poolb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.262 .717)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ii5uzUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.465 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="io0ua0x" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.179 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivYeSjc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.264 9.984)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iwX4uIb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.625 10.529)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iHNWoEe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.739 10.701)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="i55ZT3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61317 -.19704 .21148 -1.73136 10.731 10.628)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iUTRkjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15732 -.19303 -1.12456 10.78 10.628)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iSfaohe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.531 6.057)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ozh-gwb3b"/><stop offset="1" class="rq63c9eso"/></radialGradient><radialGradient id="ipRkMCd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.344 2.9)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="ijZRdpb" cx="0" cy="0" r="1" gradientTransform="matrix(2.67803 0 0 3.53252 8.307 4.002)" gradientUnits="userSpaceOnUse"><stop class="cxaqe9bxy"/><stop offset="1" class="p0efopw-a"/></radialGradient><radialGradient id="iEfaG0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.75 8.9809 -.10205 18.813 7.111)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="ox62rwbrf"/><stop offset="1" class="g4wbwbcoe"/></radialGradient><radialGradient id="iviZ2td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.86 19.291)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iZ28Hob" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.219 18.166)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="iSwgMHe" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.33 20.463)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iN9IxAg" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.196 18.582)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iPZUYwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.75 18.885)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iX54eKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.687 21.291)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iJzqndO" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.697 11.245)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="j0jku5-3m"/><stop offset="1" class="r37diw65a"/></radialGradient><radialGradient id="ip93O9c" cx="0" cy="0" r="1" gradientTransform="rotate(96.148 5.155 20.065)scale(2.87591 2.5871)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dsgtjgbbb"/><stop offset=".746" class="ofpn5ibfj"/></radialGradient><radialGradient id="iJXmFGj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.74 25.282)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ic0DIjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.74 26.577)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iuA41je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.74 27.827)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iYb2AEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.74 29.178)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><filter id="iPokwdd" width="14.3" height="12.3" x="8.372" y="18.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/></filter><filter id="ic3nR3b" width="6.538" height="5.771" x="12.014" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".325"/></filter><filter id="iamwKMc" width="2.5" height="2.5" x="18.462" y="27.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".25"/></filter><filter id="ihHtPxc" width="2.5" height="2.5" x="18.462" y="23.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".25"/></filter><filter id="ikZLETb" width="2.5" height="2.5" x="18.462" y="19.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".25"/></filter><filter id="ixiOxgM" width="1.7" height="1.7" x="19.132" y="27.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1886" result="effect2_innerShadow_4002_1886"/></filter><filter id="iZLh1sl" width="1.7" height="1.7" x="19.132" y="23.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1886" result="effect2_innerShadow_4002_1886"/></filter><filter id="igcu2oc" width="1.7" height="1.7" x="19.132" y="20.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1886" result="effect2_innerShadow_4002_1886"/></filter><filter id="iGLi7Rd" width="11.297" height="12.542" x="10.549" y="4.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1886" result="effect2_innerShadow_4002_1886"/></filter><filter id="iIW0HNd" width="3.877" height="4.9" x="13.501" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".5"/></filter><filter id="iO8Y7OS" width="2.277" height="3.3" x="14.508" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".1"/></filter><filter id="ilRo2sd" width="3.618" height="1.473" x="13.838" y="13.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="iWkxxcH" width="2.339" height="1.19" x="17.236" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/></filter><filter id="inhwmTI" width="2.339" height="1.176" x="11.979" y="7.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/></filter><filter id="ihtY4ce" width=".787" height=".696" x="17.095" y="9.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="iJYGa9d" width=".891" height=".913" x="17.934" y="9.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".1"/></filter><filter id="iPSWifb" width=".986" height="1.04" x="13.492" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".1"/></filter><filter id="inRLc0b" width=".913" height=".705" x="12.737" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="iwwSUHb" width="1.329" height="2.379" x="9.614" y="9.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".125"/></filter><filter id="ifpsBsb" width="1.947" height="2.903" x="20.108" y="9.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".25"/></filter><filter id="ig7dTwH" width="2.105" height=".86" x="12.048" y="7.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".075"/></filter><filter id="imKymca" width="2.105" height=".869" x="17.328" y="7.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".075"/></filter><filter id="iZ4zRzd" width="14.779" height="5.543" x="8.307" y="2.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/></filter><filter id="i8q7XZm" width=".675" height="2.047" x="12.554" y="3.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="iXOSoJb" width=".675" height="2.047" x="18.142" y="3.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="i6791Fd" width=".98" height="2.537" x="15.211" y="3.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".1"/></filter><filter id="iCo9d5c" width="2.238" height="1.809" x="14.522" y="17.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1886" result="effect2_innerShadow_4002_1886"/></filter><filter id="iSVBUAe" width="5.047" height="11.336" x="23.075" y="14.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.552941 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/></filter><filter id="iQsyOre" width="3.672" height="4.703" x="23.537" y="15.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.662745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/><feGaussianBlur result="effect2_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="ibivcid" width="4.468" height="5.556" x="23.304" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1886"/></filter><filter id="iuErZKk" width="2.097" height=".3" x="23.674" y="25.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="igoEA1c" width="2.097" height=".3" x="23.596" y="27.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><filter id="iXgCzuc" width="2.097" height=".3" x="23.674" y="28.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1886" stdDeviation=".05"/></filter><linearGradient id="i8LR0Pd" x1="9.996" x2="10.783" y1="8.409" y2="8.377" gradientUnits="userSpaceOnUse"><stop class="fb1dqpbpv"/><stop offset="1" class="nu57mx1sw"/></linearGradient><linearGradient id="iqNi5re" x1="20.818" x2="20.818" y1="7.697" y2="9.26" gradientUnits="userSpaceOnUse"><stop class="hcfjk_btp"/><stop offset="1" class="p-7lm7ody"/></linearGradient><linearGradient id="iclDghK" x1="22.829" x2="26.073" y1="25.875" y2="25.875" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="inP0Oyd" x1="7.812" x2="7.812" y1="30.994" y2="16.932" gradientUnits="userSpaceOnUse"><stop class="l0qpfdqgo"/><stop offset="1" class="i1-orb7ke"/></linearGradient><linearGradient id="ijJ9Suc" x1="8.672" x2="8.094" y1="26.619" y2="26.619" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="i8IFnqb" x1="8.672" x2="12.608" y1="27.206" y2="27.206" gradientUnits="userSpaceOnUse"><stop class="fj7z_vbcj"/><stop offset="1" class="zab3c9ypw"/></linearGradient><linearGradient id="ioTXyId" x1="16.28" x2="13.319" y1="22.125" y2="18.741" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iu0EE4d" x1="20.5" x2="19.232" y1="27.639" y2="29.046" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iYvtXXn" x1="20.5" x2="19.232" y1="23.999" y2="25.405" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iI41UMM" x1="20.5" x2="19.232" y1="20.369" y2="21.776" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i4cj08b" x1="20.846" x2="16.46" y1="12.572" y2="12.572" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iFwyLLo" x1="16.485" x2="15.647" y1="11.561" y2="11.596" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i5wRUhb" x1="15.647" x2="15.647" y1="12.7" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="ihDQkVb" x1="15.647" x2="15.647" y1="9.866" y2="10.542" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="ifBJf6c" x1="14.445" x2="14.763" y1="14.271" y2="13.437" gradientUnits="userSpaceOnUse"><stop class="rwnwb2y0z"/><stop offset="1" class="ny1jq5bdu"/></linearGradient><linearGradient id="iOdp95c" x1="18.607" x2="18.293" y1="10.024" y2="10.217" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iryQq3Q" x1="14.209" x2="13.895" y1="10.024" y2="10.218" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihIaqQd" x1="22.083" x2="20.876" y1="10.051" y2="12.227" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iHylZPe" x1="9.797" x2="11.255" y1="10.755" y2="10.628" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iML575d" x1="21.082" x2="21.082" y1="9.673" y2="11.576" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="idrl29d" x1="16.281" x2="16.281" y1="7.776" y2="7.088" gradientUnits="userSpaceOnUse"><stop class="gjkvqmbnm"/><stop offset="1" class="f1s8bobxq"/></linearGradient><linearGradient id="i7dHb5c" x1="13.027" x2="12.449" y1="5.628" y2="5.53" gradientUnits="userSpaceOnUse"><stop offset=".297" class="u7axe2baw"/><stop offset="1" class="dv8o3t25w"/></linearGradient><linearGradient id="i6pT3RP" x1="18.289" x2="18.922" y1="5.437" y2="5.53" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ahul9kboj"/><stop offset="1" class="ongktybvd"/></linearGradient><linearGradient id="igCFrRd" x1="15.991" x2="15.991" y1="5.773" y2="3.745" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ztvu2mbem"/><stop offset="1" class="bm3jemb-u"/></linearGradient><linearGradient id="iDpui5Q" x1="16.375" x2="17.359" y1="17.994" y2="19.166" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="i6NqMhe" x1="15.891" x2="15.891" y1="18.885" y2="17.446" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="idQbWuc" x1="27.332" x2="23.304" y1="28.04" y2="28.04" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iw5CDNb" x1="23.824" x2="25.533" y1="26.033" y2="26.033" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i16u2Bb" x1="23.746" x2="25.455" y1="27.338" y2="27.338" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iKacdXb" x1="23.824" x2="25.533" y1="28.643" y2="28.643" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cook-light" /></template>
<style>
.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ahul9kboj {
  stop-color: var(--svg-color--a499b2, #A499B2);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3_m6tbiu {
  stop-color: var(--svg-color--b8a4be, #B8A4BE);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.blny5fbqc {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
  stop-opacity: 0;
}

.bm3jemb-u {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c22lxt0bf {
  stop-color: var(--svg-color--d49998, #D49998);
  stop-opacity: 0;
}

.c3pazcc9s {
  d: path("M15.652 15.477c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.c7uaskqvv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.765 9.682c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.cbnipmb4g {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.652 15.477c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.cdwb3bbdw {
  fill-rule: evenodd;
  d: path("m18.242 5.882l.475-1.847v1.847z");
}

.cho0wwbxj {
  d: path("M9.996 7.354h.96v2.608h-.96z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm6t0pbhv {
  cx: 13.193px;
  cy: 9.875px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.cma9xwb_i {
  d: path("M20.508 12.136c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.cu07-zbpq {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.16 10.368l-.634 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.542-.408-.661 0");
}

.cxaqe9bxy {
  stop-color: var(--svg-color--e7d1cd, #E7D1CD);
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9a-s9bqe {
  stop-color: var(--svg-color--a191a5, #A191A5);
  stop-opacity: 0;
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dsgtjgbbb {
  stop-color: var(--svg-color--e4976b, #E4976B);
}

.dv8o3t25w {
  stop-color: var(--svg-color--9183a0, #9183A0);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e1zowv8mu {
  cx: 25.348px;
  cy: 17.721px;
  rx: 1.711px;
  ry: 2.227px;
}

.e6gu6dbjq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.038 9.221c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.ej8z3qyin {
  d: path("M13.46 18.691c.67-.924 1.703-1.194 2.096-1.245c.205.83.308 2.667-.684 3.564c-.635.574-1.078.722-1.67.786c-.163.018-.27-.164-.222-.321c.03-.101.051-.22.053-.366c.01-.634-.108-1.68.426-2.418");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.enli_kbua {
  fill: var(--svg-color--eca779, #ECA779);
  d: path("M26.051 21.18c0-.405.26-.757.568-1.02c.605-.517 1.003-1.392 1.003-2.384c0-1.588-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.287-2.273 2.875c0 .992.398 1.867 1.002 2.384c.309.263.568.615.568 1.02v5.057h1.406z");
}

.eth6kt59r {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.284 13.41c.394.206.863.323 1.363.323c.504 0 .969-.117 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.987-.28l2.946.253m-2.946-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.208.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.869a1.94 1.94 0 0 1-1.625-.868m3.208-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.584-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f0lc8cb-l {
  d: path("M17.83 9.493a.893.893 0 0 1 .86 1.128h-1.723a.896.896 0 0 1 .864-1.128");
}

.f1s8bobxq {
  stop-color: var(--svg-color--9482a1, #9482A1);
  stop-opacity: 0;
}

.f4rh3ucjs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 25.955h1.797");
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.fb1dqpbpv {
  stop-color: var(--svg-color--554743, #554743);
}

.fg0e2bc1h {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
}

.fj7z_vbcj {
  stop-color: var(--svg-color--958d9d, #958D9D);
}

.fjyr3161v {
  stop-color: var(--svg-color--730620, #730620);
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

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g37mewbhm {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.273 8.335c.257-.185.898-.51 1.656-.382");
}

.g4wbwbcoe {
  stop-color: var(--svg-color--a79da9, #A79DA9);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gjkvqmbnm {
  stop-color: var(--svg-color--9482a1, #9482A1);
}

.grfxoxf1b {
  fill: var(--svg-color--c5a9b6, #C5A9B6);
  d: path("M19.712 21.762a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.h5wfhsdxa {
  d: path("M26.655 23.064a.97.97 0 0 1 .967.967v2.215h-1.934V24.03a.976.976 0 0 1 .967-.967");
}

.h63qsw72a {
  d: path("M20.338 7.354h.96v2.608h-.96z");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hcfjk_btp {
  stop-color: var(--svg-color--363535, #363535);
}

.hgez_ckwa {
  d: path("M8.672 17.98a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.hm5-ozbqx {
  stop-color: var(--svg-color--cfc5da, #CFC5DA);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i1din9b9j {
  d: path("M10.822 13.652a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.278-4.388.366-6.27c-.011-.768-.657-.773-1.421-.805h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.376.799-3.376 2.665c0 1.86.15 4.405.273 6.27");
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.iwxs3cf0k {
  d: path("M20.569 12.227c.065-1.064.129-2.127.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.izufo8bpf {
  fill-rule: evenodd;
  d: path("m13.129 5.882l-.475-1.847v1.847z");
}

.j0jku5-3m {
  stop-color: var(--svg-color--f4b183, #F4B183);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jioigf_uc {
  d: path("M26.051 21.18c0-.405.26-.757.568-1.02c.605-.517 1.003-1.392 1.003-2.384c0-1.588-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.287-2.273 2.875c0 .992.398 1.867 1.002 2.384c.309.263.568.615.568 1.02v5.057h1.406z");
}

.juxik1ilm {
  d: path("M18.626 10.268a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.jvaz6dbql {
  fill: var(--svg-color--c3b3cb, #C3B3CB);
  d: path("M20.462 28.282a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.jvsy5c46p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.746 27.26h1.797");
}

.jxxebtbrj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.256 9.221c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.k4hskrbnq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 28.565h1.797");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kxtk97b-s {
  d: path("M15.385 17.503c-.385.032-1.404.252-2.102 1.142c-.47.6-.498 1.44-.52 2.069q-.005.177-.014.326c-.01.145-.035.263-.07.363c-.054.154.04.341.2.331c.58-.036 1.018-.162 1.664-.705c.493-.413.743-1.062.851-1.716c.044.661.228 1.332.677 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.232-.31a1.3 1.3 0 0 1-.034-.368q.005-.151.018-.326c.04-.628.095-1.467-.313-2.11c-.607-.955-1.6-1.274-1.979-1.344c-.047.16-.092.359-.128.582a5 5 0 0 0-.07-.592");
}

.kz1-kyj0l {
  stop-color: var(--svg-color--a191a5, #A191A5);
}

.l0qpfdqgo {
  stop-color: var(--svg-color--baa6bf, #BAA6BF);
}

.l1ijt7pks {
  d: path("M17.765 9.682c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.m_titrr7w {
  fill: var(--svg-color--000, #000);
  d: path("M17.32 10.386c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.m22si5bvo {
  d: path("M15.411 3.745h.58v2.137h-.58z");
}

.m6lhrcc1m {
  stop-color: var(--svg-color--e1d7df, #E1D7DF);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mnnhslsrw {
  d: path("M13.463 9.493a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.mpl2hj91k {
  d: path("M15.647 13.783c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mvu-d8qbf {
  d: path("M19.982 21.617a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.mzk447emc {
  d: path("M14.278 10.281c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n9mbalbjx {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.38 8.171a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nu57mx1sw {
  stop-color: var(--svg-color--282321, #282321);
}

.nx5hvxbaz {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.236 8.055a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.ny1jq5bdu {
  stop-color: var(--svg-color--dfaaa1, #DFAAA1);
  stop-opacity: 0;
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.ob7bcwbug {
  cx: 13.193px;
  cy: 9.875px;
  rx: 0.39px;
  ry: 0.197px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpn5ibfj {
  stop-color: var(--svg-color--e29457, #E29457);
}

.ongktybvd {
  stop-color: var(--svg-color--a499b2, #A499B2);
  stop-opacity: 0;
}

.ox62rwbrf {
  stop-color: var(--svg-color--e1dbe8, #E1DBE8);
}

.ozh-gwb3b {
  stop-color: var(--svg-color--ab96ac, #AB96AC);
}

.p-7lm7ody {
  stop-color: var(--svg-color--272628, #272628);
}

.p0efopw-a {
  stop-color: var(--svg-color--b8a5ca, #B8A5CA);
  stop-opacity: 0;
}

.p8_zej1gv {
  fill: var(--svg-color--000, #000);
  d: path("M13.974 10.386a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.pawfg2lic {
  d: path("M20.609 11.576q.057-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qk3h5tshn {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
  stop-opacity: 0;
}

.ql78zhb7e {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwvc_obpa {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.264 10.172l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.qzno1cccr {
  d: path("M23.304 25.303c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.03a.731.731 0 0 1-.319-1.388a.735.735 0 0 1 0-1.315a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r37diw65a {
  stop-color: var(--svg-color--f4b183, #F4B183);
  stop-opacity: 0;
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rokvf6b0z {
  d: path("M21.727 5.932H9.675q.026.046.027.102v1.051c0 .249.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.03a.2.2 0 0 1 .025-.098");
}

.rq63c9eso {
  stop-color: var(--svg-color--c8bdc7, #C8BDC7);
}

.rwnwb2y0z {
  stop-color: var(--svg-color--dfaaa1, #DFAAA1);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.rxhgcccxt {
  d: path("M22.672 30.007h4v-3.501c0-3.422-1.554-6.482-4-8.499z");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sq5xszbgd {
  d: path("M10.241 2.092a1.933 1.933 0 0 0-.681 3.744a.215.215 0 0 1 .142.197v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.03c0-.089.058-.166.141-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t6pr07xmi {
  d: path("M8.672 18.007h10.052c2.177 0 3.948 1.796 3.948 4.004v7.996h-14z");
}

.tb19eccqx {
  stop-color: var(--svg-color--b8a4be, #B8A4BE);
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tvis7hbtj {
  d: path("M10.593 9.028a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.u7axe2baw {
  stop-color: var(--svg-color--9183a0, #9183A0);
}

.u892n_fxl {
  d: path("M14.984 17.565c.19-.063.44-.119.707-.119s.517.056.707.12a.39.39 0 0 1 .255.45c-.093.486-.27.8-.464.989a.5.5 0 0 1-.267.13c-.11.02-.338.032-.477 0a.43.43 0 0 1-.252-.13c-.194-.189-.371-.503-.463-.99a.39.39 0 0 1 .254-.45");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v5ycnsq6q {
  d: path("M10.785 12.136a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vhcq0yb2g {
  d: path("M20.732 28.138a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vuu318b4c {
  stop-color: var(--svg-color--730620, #730620);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.ws083288l {
  stop-color: var(--svg-color--b46361, #B46361);
}

.wxh3co6vs {
  d: path("M10.61 9.689a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.x5m_r-40z {
  d: path("M23.081 18.362H8.232a10.94 10.94 0 0 1 7.42-2.885c3.484 0 5.153.812 7.43 2.885");
}

.xc5vz2nwi {
  d: path("m15.264 10.172l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xqmi19bsb {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.208 8.296c-.282-.297-.898-.509-1.655-.381");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yitm6bbcf {
  fill: var(--svg-color--c2b3c3, #C2B3C3);
  d: path("M19.712 25.392a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z69a7kb1f {
  d: path("M17.855 18.691c-.67-.924-1.704-1.194-2.097-1.245c-.205.83-.308 2.667.684 3.564c.635.574 1.077.722 1.67.786c.163.018.269-.164.221-.321c-.03-.101-.05-.22-.053-.366c-.009-.634.11-1.68-.425-2.418");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zab3c9ypw {
  stop-color: var(--svg-color--a8a0af, #A8A0AF);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.ztvu2mbem {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
}

.zxda46ott {
  d: path("M19.982 25.247a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

</style>
