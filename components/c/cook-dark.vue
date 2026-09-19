<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6AJzEe)" class="cho0wwbxj"/><path fill="url(#iHO0aLd)" class="h63qsw72a"/><path class="z8h9scccv"/><path fill="url(#iF5wVCb)" class="bnk77m7vp"/><path fill="url(#iclDghK)" class="yz1szqxmz"/><path fill="url(#i3eEjnr)" class="yz1szqxmz"/><path fill="url(#iFjjgIc)" class="hgez_ckwa"/><path fill="url(#ijJ9Suc)" class="hgez_ckwa"/><path fill="url(#i1e4Iad)" class="hgez_ckwa"/><g filter="url(#ih6i26c)"><path fill="url(#iSRYsze)" class="p5552iurb"/><path fill="url(#iQiOQqb)" class="p5552iurb"/></g><path fill="url(#iEhBste)" class="p5552iurb"/><path fill="url(#ir5BRDx)" class="p5552iurb"/><g filter="url(#iBK9rGd)"><path fill="url(#ioTXyId)" class="c2mr_87lm"/></g><path fill="url(#iZO70ib)" class="q6o6udbiy"/><path fill="url(#iuF7Ptd)" class="q6o6udbiy"/><g filter="url(#iYMxntb)"><path class="tqc-acwnz"/></g><g filter="url(#i4MOOUd)"><path class="g5d-ge_7s"/></g><g filter="url(#irvmplb)"><path class="liagiztua"/></g><g filter="url(#iAErjud)"><path fill="url(#ijhc7Dt)" class="r-suar6rb"/></g><g filter="url(#iSp3Kgd)"><path fill="url(#iYvtXXn)" class="zxda46ott"/></g><g filter="url(#iZlFhMb)"><path fill="url(#iaeG8Tc)" class="mvu-d8qbf"/></g><path fill="url(#i9oslfU)" class="h5wfhsdxa"/><path fill="url(#isTD6Pc)" class="h5wfhsdxa"/><path fill="url(#imJyySb)" class="b6fho8cbp"/><path fill="url(#iVVynLb)" class="v5ycnsq6q"/><g filter="url(#inAQWOc)"><path fill="url(#isScSne)" class="qscu39bls"/></g><path fill="url(#iTo7rtb)" class="qscu39bls"/><path fill="url(#iOYd7Le)" class="qscu39bls"/><path fill="url(#i3pA2ve)" class="qscu39bls"/><path fill="url(#il1p8ic)" class="qscu39bls"/><path fill="url(#iZHmmmc)" class="qscu39bls"/><path fill="url(#iuJ9m3d)" class="qscu39bls"/><path fill="url(#iHJhsHd)" class="qscu39bls"/><path fill="url(#iXbQcAd)" class="qscu39bls"/><path fill="url(#iQRsFSb)" class="qscu39bls"/><path fill="url(#iHyBCtd)" class="qscu39bls"/><path fill="url(#ifG2xip)" class="qscu39bls"/><g filter="url(#iCGFAQb)"><path class="wixqmvb1w"/></g><g filter="url(#iwx37fb)"><path class="zw3ek-w3v"/><path fill="url(#iKYwHEU)" class="oc4pkvgaa"/><path fill="url(#iMKYnUS)" class="oc4pkvgaa"/><path fill="url(#ipLxODe)" class="oc4pkvgaa"/><path fill="url(#iL1VMde)" class="oc4pkvgaa"/><path fill="url(#iIToSMc)" class="oc4pkvgaa"/></g><g filter="url(#iCSUpgb)"><path stroke="url(#irmFkVd)" class="gy5hrg9st"/></g><path fill="url(#idmgePc)" class="iw6o86bel"/><g filter="url(#iN9NfBc)"><path class="n9mbalbjx"/></g><g filter="url(#i3y8kfS)"><path class="ylk__q3fj"/></g><path class="x_wo803sx"/><path fill="url(#ioBcoFw)" class="f0lc8cb-l"/><path class="vx2mszbsl"/><g filter="url(#iiazyJb)"><path class="a9ai_pbjk"/><path fill="url(#i8poolb)" class="x-c39ztfn"/></g><g filter="url(#iRYg4Uc)"><path fill="url(#iOdp95c)" class="xrsv2ub3b"/></g><path class="v68h42b7d"/><path fill="url(#ii5uzUd)" class="zcwozlblh"/><path class="hq3hs4qwo"/><g filter="url(#iMnAw8c)"><path fill="url(#i10YU7c)" class="l78-nlbha"/></g><g filter="url(#iFCm5ye)"><ellipse transform="rotate(-27.914 13.193 9.874)" class="jxkioqbgf"/><ellipse fill="url(#io0ua0x)" transform="rotate(-27.914 13.193 9.874)" class="um-bsxb3u"/></g><path fill="url(#imlyWXb)" class="k43kdziwc"/><path fill="url(#ifSjEMd)" class="k43kdziwc"/><path fill="url(#i7RyTXb)" class="k43kdziwc"/><path fill="url(#i1l7FMe)" class="k43kdziwc"/><path fill="url(#iOilrHc)" class="tvis7hbtj"/><path fill="url(#ia76BQe)" class="tvis7hbtj"/><g filter="url(#ihykDmb)"><path fill="url(#iVWureP)" class="q2qnqo4ln"/></g><g filter="url(#iE02bxd)"><path fill="url(#iKS8xHe)" class="t8nu1bc7r"/></g><g filter="url(#iOhA6Jb)"><path class="awuj3yb3a"/></g><g filter="url(#iNNGV0c)"><path class="ctm5nzbvf"/></g><g filter="url(#ihaQfxd)"><path fill="url(#iZHyAlb)" class="ys4clom6y"/><path fill="url(#ipRkMCd)" class="ys4clom6y"/></g><path fill="url(#iEfaG0b)" class="f2qtmlsqy"/><path fill="url(#iENEYDk)" class="f2qtmlsqy"/><g filter="url(#iXd0RVd)"><path fill="url(#i7dHb5c)" clip-rule="evenodd" class="izufo8bpf"/></g><g filter="url(#i50g3Ke)"><path fill="url(#iaBcXVb)" clip-rule="evenodd" class="cdwb3bbdw"/></g><g filter="url(#i4TMKpd)"><path fill="url(#iEr1oac)" class="m22si5bvo"/></g><path fill="url(#iviZ2td)" class="myqq0epvb"/><path fill="url(#iZ28Hob)" class="myqq0epvb"/><path fill="url(#iSwgMHe)" class="myqq0epvb"/><path fill="url(#iN9IxAg)" class="ygege63ax"/><path fill="url(#iDpui5Q)" class="ygege63ax"/><path fill="url(#iuH4NEW)" class="ygege63ax"/><path fill="url(#iX54eKd)" class="ygege63ax"/><g filter="url(#inkghAe)"><path fill="url(#i6NqMhe)" class="i8ybtsiju"/></g><g filter="url(#iQb4zhb)"><path class="mnbq8nqxg"/><path fill="url(#i6PeWOc)" class="wjon1acce"/></g><g filter="url(#iT1AFPd)"><ellipse fill="url(#iJ28PId)" class="e1zowv8mu"/></g><g filter="url(#i4mU4eb)"><path fill="url(#iiMzoFb)" class="elljabbti"/><path fill="url(#izbbr0d)" class="elljabbti"/><path fill="url(#ieolzEO)" class="elljabbti"/><path fill="url(#iKvzyGd)" class="elljabbti"/><path fill="url(#ivfY6Fb)" class="elljabbti"/></g><g filter="url(#iNgvHac)"><path stroke="url(#i35Hx7c)" class="f4rh3ucjs"/></g><g filter="url(#i3W3wcc)"><path stroke="url(#irheozd)" class="jvsy5c46p"/></g><g filter="url(#ihCOQrZ)"><path stroke="url(#i8hT2ce)" class="k4hskrbnq"/></g><defs><radialGradient id="iF5wVCb" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.742 57.515)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="i3eEjnr" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 23.684 30.21)" gradientUnits="userSpaceOnUse"><stop class="q2rhgqb4s"/><stop offset="1" class="fs29nabkl"/><stop offset="1" class="sli_wqbvh"/></radialGradient><radialGradient id="i1e4Iad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.125 30.713)" gradientUnits="userSpaceOnUse"><stop class="g2ynuf2dq"/><stop offset="1" class="ef22fkbzm"/></radialGradient><radialGradient id="iSRYsze" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 20.726 19.684)" gradientUnits="userSpaceOnUse"><stop class="m6lhrcc1m"/><stop offset="1" class="hm5-ozbqx"/></radialGradient><radialGradient id="iQiOQqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.39 32.457)" gradientUnits="userSpaceOnUse"><stop class="fg0e2bc1h"/><stop offset="1" class="qk3h5tshn"/></radialGradient><radialGradient id="iEhBste" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.504 16.03)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iZO70ib" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 8.994 10.11)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iuF7Ptd" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.602 8.62)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="fjyr3161v"/><stop offset="1" class="vuu318b4c"/></radialGradient><radialGradient id="i9oslfU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68781 1.6831 -2.07966 -2.08548 27.712 23.328)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="isTD6Pc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.386 23.545)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="imJyySb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.7 20.574)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iVVynLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.59 12.318)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="isScSne" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26686 0 0 -9.24801 18.479 10.886)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iOYd7Le" cx="0" cy="0" r="1" gradientTransform="rotate(94.739 6.333 10.423)scale(12.4661 10.3994)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i3pA2ve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.43169 0 18.115 9.574)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="il1p8ic" cx="0" cy="0" r="1" gradientTransform="matrix(.00395 -1.09427 1.19972 .00433 13.332 9.62)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iZHmmmc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.55937 .53641 -1.36019 -21.70422 19.108 11.874)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iuJ9m3d" cx="0" cy="0" r="1" gradientTransform="matrix(4.10339 -2.64829 .96652 1.49757 10.142 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iHJhsHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23643 2.49743 -1.00564 -.0952 21.236 7.97)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iXbQcAd" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.388 8.036)scale(3.37573 2.79652)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="ifG2xip" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.6875 -5.38472 0 15.697 7.58)" gradientUnits="userSpaceOnUse"><stop class="e8_7lrbjf"/><stop offset="1" class="itlfwsb4w"/></radialGradient><radialGradient id="iMKYnUS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.113 12.247)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iL1VMde" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.23 11.677)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="idmgePc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.647 14.426)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="ioBcoFw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.829 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8poolb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.262 .717)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ii5uzUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.465 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="io0ua0x" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.179 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifSjEMd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.264 9.984)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i7RyTXb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.625 10.529)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="i1l7FMe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.739 10.701)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="ia76BQe" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.026 9.337)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iVWureP" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 10.781 10.627)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iZHyAlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.531 6.056)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ysetj63ow"/><stop offset="1" class="e1v2e-byl"/></radialGradient><radialGradient id="ipRkMCd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.344 2.9)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iEfaG0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.75 8.9809 -.10205 18.813 7.111)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="ox62rwbrf"/><stop offset="1" class="g4wbwbcoe"/></radialGradient><radialGradient id="iviZ2td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 14.86 19.291)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="iZ28Hob" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.219 18.166)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="iSwgMHe" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.33 20.463)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iN9IxAg" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.196 18.582)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="iuH4NEW" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 15.75 18.883)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iX54eKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 18.687 21.291)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="i6PeWOc" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.697 11.245)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="via-_dbpm"/><stop offset="1" class="bt1_2zb2r"/></radialGradient><radialGradient id="iJ28PId" cx="0" cy="0" r="1" gradientTransform="matrix(2.27907 0 0 3.27907 24.419 17.9)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="uelaalb7d"/><stop offset=".746" class="i5m4wsx9z"/></radialGradient><radialGradient id="izbbr0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.74 25.282)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ieolzEO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.74 26.576)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iKvzyGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.74 27.826)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ivfY6Fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.74 29.178)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><filter id="ih6i26c" width="14.3" height="12.3" x="8.372" y="18.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/></filter><filter id="iBK9rGd" width="6.538" height="5.771" x="12.014" y="16.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".325"/></filter><filter id="iYMxntb" width="2.5" height="2.5" x="18.462" y="27.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".25"/></filter><filter id="i4MOOUd" width="2.5" height="2.5" x="18.462" y="23.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".25"/></filter><filter id="irvmplb" width="2.5" height="2.5" x="18.462" y="19.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".25"/></filter><filter id="iAErjud" width="1.7" height="1.7" x="19.132" y="27.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1874" result="effect2_innerShadow_4002_1874"/></filter><filter id="iSp3Kgd" width="1.7" height="1.7" x="19.132" y="23.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1874" result="effect2_innerShadow_4002_1874"/></filter><filter id="iZlFhMb" width="1.7" height="1.7" x="19.132" y="20.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1874" result="effect2_innerShadow_4002_1874"/></filter><filter id="inAQWOc" width="11.297" height="12.542" x="10.549" y="4.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1874" result="effect2_innerShadow_4002_1874"/></filter><filter id="iCGFAQb" width="3.877" height="4.9" x="13.501" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".5"/></filter><filter id="iwx37fb" width="2.277" height="3.3" x="14.508" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".1"/></filter><filter id="iCSUpgb" width="3.618" height="1.473" x="13.838" y="13.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="iN9NfBc" width="2.339" height="1.19" x="17.236" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/></filter><filter id="i3y8kfS" width="2.339" height="1.176" x="11.979" y="7.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/></filter><filter id="iiazyJb" width=".787" height=".696" x="17.095" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="iRYg4Uc" width=".891" height=".913" x="17.934" y="9.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".1"/></filter><filter id="iMnAw8c" width=".986" height="1.04" x="13.492" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".1"/></filter><filter id="iFCm5ye" width=".913" height=".705" x="12.737" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="ihykDmb" width="1.329" height="2.379" x="9.614" y="9.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".125"/></filter><filter id="iE02bxd" width="1.947" height="2.903" x="20.108" y="9.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".25"/></filter><filter id="iOhA6Jb" width="2.405" height="1.16" x="11.898" y="7.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".125"/></filter><filter id="iNNGV0c" width="2.405" height="1.169" x="17.178" y="7.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".125"/></filter><filter id="ihaQfxd" width="14.779" height="5.543" x="8.307" y="2.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/></filter><filter id="iXd0RVd" width=".675" height="2.047" x="12.554" y="3.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="i50g3Ke" width=".675" height="2.047" x="18.142" y="3.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="i4TMKpd" width=".98" height="2.537" x="15.211" y="3.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".1"/></filter><filter id="inkghAe" width="2.238" height="1.809" x="14.522" y="17.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1874" result="effect2_innerShadow_4002_1874"/></filter><filter id="iQb4zhb" width="5.047" height="11.336" x="23.075" y="14.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.521569 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/></filter><filter id="iT1AFPd" width="3.672" height="4.703" x="23.537" y="15.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.647059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/><feGaussianBlur result="effect2_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="i4mU4eb" width="4.468" height="5.556" x="23.304" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1874"/></filter><filter id="iNgvHac" width="2.097" height=".3" x="23.674" y="25.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="i3W3wcc" width="2.097" height=".3" x="23.596" y="27.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><filter id="ihCOQrZ" width="2.097" height=".3" x="23.674" y="28.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1874" stdDeviation=".05"/></filter><linearGradient id="i6AJzEe" x1="10.476" x2="10.476" y1="7.869" y2="9.962" gradientUnits="userSpaceOnUse"><stop class="qi731gbjb"/><stop offset="1" class="zmama0ttw"/></linearGradient><linearGradient id="iHO0aLd" x1="20.818" x2="20.818" y1="7.697" y2="9.26" gradientUnits="userSpaceOnUse"><stop class="ty8nzq04x"/><stop offset="1" class="uf4kgmbxa"/></linearGradient><linearGradient id="iclDghK" x1="22.829" x2="26.073" y1="25.875" y2="25.875" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iFjjgIc" x1="7.812" x2="7.812" y1="30.994" y2="16.932" gradientUnits="userSpaceOnUse"><stop offset=".06" class="rvini-b1k"/><stop offset="1" class="si_znv48i"/><stop offset="1" class="akw2ge0vx"/></linearGradient><linearGradient id="ijJ9Suc" x1="8.672" x2="8.094" y1="26.619" y2="26.619" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="ir5BRDx" x1="8.672" x2="12.608" y1="27.205" y2="27.205" gradientUnits="userSpaceOnUse"><stop class="fj7z_vbcj"/><stop offset="1" class="zab3c9ypw"/></linearGradient><linearGradient id="ioTXyId" x1="16.28" x2="13.319" y1="22.125" y2="18.741" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="ijhc7Dt" x1="20.5" x2="19.232" y1="27.639" y2="29.045" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iYvtXXn" x1="20.5" x2="19.232" y1="23.999" y2="25.405" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iaeG8Tc" x1="20.5" x2="19.232" y1="20.369" y2="21.775" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iTo7rtb" x1="20.846" x2="16.46" y1="12.572" y2="12.572" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iQRsFSb" x1="15.697" x2="15.697" y1="17.139" y2="16.498" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iHyBCtd" x1="20.625" x2="20.25" y1="12.744" y2="12.721" gradientUnits="userSpaceOnUse"><stop class="vh02o1b7a"/><stop offset="1" class="at0fzabbu"/></linearGradient><linearGradient id="iKYwHEU" x1="16.485" x2="15.647" y1="11.561" y2="11.596" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ipLxODe" x1="15.647" x2="15.647" y1="12.7" y2="12.235" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iIToSMc" x1="15.647" x2="15.647" y1="9.746" y2="10.542" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="irmFkVd" x1="14.445" x2="14.763" y1="14.271" y2="13.437" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iOdp95c" x1="18.607" x2="18.293" y1="10.024" y2="10.217" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i10YU7c" x1="14.209" x2="13.895" y1="10.024" y2="10.217" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imlyWXb" x1="22.083" x2="20.876" y1="10.051" y2="12.227" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iOilrHc" x1="9.797" x2="11.255" y1="10.755" y2="10.628" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iKS8xHe" x1="21.082" x2="21.082" y1="9.673" y2="11.576" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iENEYDk" x1="16.281" x2="16.281" y1="7.775" y2="7.088" gradientUnits="userSpaceOnUse"><stop class="gjkvqmbnm"/><stop offset="1" class="f1s8bobxq"/></linearGradient><linearGradient id="i7dHb5c" x1="13.027" x2="12.449" y1="5.628" y2="5.53" gradientUnits="userSpaceOnUse"><stop offset=".297" class="u7axe2baw"/><stop offset="1" class="dv8o3t25w"/></linearGradient><linearGradient id="iaBcXVb" x1="18.289" x2="18.922" y1="5.436" y2="5.53" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ahul9kboj"/><stop offset="1" class="ongktybvd"/></linearGradient><linearGradient id="iEr1oac" x1="15.991" x2="15.991" y1="5.772" y2="3.745" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ztvu2mbem"/><stop offset="1" class="bm3jemb-u"/></linearGradient><linearGradient id="iDpui5Q" x1="16.375" x2="17.359" y1="17.994" y2="19.166" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="i6NqMhe" x1="15.891" x2="15.891" y1="18.885" y2="17.446" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="iiMzoFb" x1="27.332" x2="23.304" y1="28.04" y2="28.04" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="i35Hx7c" x1="23.824" x2="25.533" y1="26.033" y2="26.033" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="irheozd" x1="23.746" x2="25.455" y1="27.338" y2="27.338" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i8hT2ce" x1="23.824" x2="25.533" y1="28.643" y2="28.643" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cook-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a9ai_pbjk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.765 9.682c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.326-.135.39-.05");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ahul9kboj {
  stop-color: var(--svg-color--a499b2, #A499B2);
}

.akw2ge0vx {
  stop-color: var(--svg-color--9b9598, #9B9598);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.at0fzabbu {
  stop-color: var(--svg-color--6c5c5a, #6C5C5A);
  stop-opacity: 0;
}

.awuj3yb3a {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.273 8.334c.257-.184.898-.508 1.656-.381");
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b6fho8cbp {
  d: path("M20.508 12.136c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
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

.bm3jemb-u {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bnk77m7vp {
  d: path("M15.652 15.477c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.502c0-3.421-1.554-6.481-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.bt1_2zb2r {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
  stop-opacity: 0;
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c2mr_87lm {
  d: path("M15.385 17.503c-.385.032-1.404.252-2.102 1.142c-.47.599-.498 1.44-.52 2.069q-.005.176-.014.326q-.016.216-.07.362c-.054.155.04.342.2.332c.58-.036 1.018-.163 1.664-.705c.493-.413.743-1.063.851-1.717c.044.662.228 1.333.677 1.792c.59.604 1.013.774 1.587.867c.158.025.27-.152.232-.31a1.3 1.3 0 0 1-.034-.369q.005-.15.018-.325c.04-.628.095-1.468-.313-2.11c-.607-.955-1.6-1.274-1.979-1.345c-.047.16-.092.36-.128.583a5 5 0 0 0-.07-.592");
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
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

.ctm5nzbvf {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.208 8.296c-.282-.298-.898-.51-1.655-.382");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dv8o3t25w {
  stop-color: var(--svg-color--9183a0, #9183A0);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1v2e-byl {
  stop-color: var(--svg-color--cac5ce, #CAC5CE);
}

.e1zowv8mu {
  cx: 25.348px;
  cy: 17.721px;
  rx: 1.711px;
  ry: 2.227px;
}

.e8_7lrbjf {
  stop-color: var(--svg-color--352028, #352028);
}

.ef22fkbzm {
  stop-color: var(--svg-color--ac9fb8, #AC9FB8);
  stop-opacity: 0;
}

.elljabbti {
  d: path("M23.304 25.303c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.03a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
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

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f2qtmlsqy {
  d: path("M21.727 5.932H9.675q.026.046.027.101v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.03a.2.2 0 0 1 .025-.098");
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

.fg0e2bc1h {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fj7z_vbcj {
  stop-color: var(--svg-color--958d9d, #958D9D);
}

.fjyr3161v {
  stop-color: var(--svg-color--730620, #730620);
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g2ynuf2dq {
  stop-color: var(--svg-color--ac9fb8, #AC9FB8);
}

.g4wbwbcoe {
  stop-color: var(--svg-color--a79da9, #A79DA9);
}

.g5d-ge_7s {
  fill: var(--svg-color--b2a7be, #B2A7BE);
  d: path("M19.712 25.392a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gjkvqmbnm {
  stop-color: var(--svg-color--9482a1, #9482A1);
}

.gy5hrg9st {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.284 13.41a2.96 2.96 0 0 0 1.363.323a2.94 2.94 0 0 0 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.987-.28l2.946.253m-2.946-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.208.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.868a1.94 1.94 0 0 1-1.625-.867m3.208-.028a1.9 1.9 0 0 1-1.583.845a1.9 1.9 0 0 1-1.584-.845m-.041.027v.001l.041-.028m-.041.027l.041-.027");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h5wfhsdxa {
  d: path("M26.655 23.064a.97.97 0 0 1 .967.967v2.215h-1.934V24.03a.976.976 0 0 1 .967-.967");
}

.h63qsw72a {
  d: path("M20.338 7.354h.96v2.608h-.96z");
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
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

.hq3hs4qwo {
  fill: var(--svg-color--000, #000);
  d: path("M13.974 10.385a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.i5m4wsx9z {
  stop-color: var(--svg-color--d68e4a, #D68E4A);
}

.i8ybtsiju {
  d: path("M14.984 17.565c.19-.063.44-.12.707-.12s.517.057.707.12a.39.39 0 0 1 .255.45c-.093.487-.27.8-.464.99a.5.5 0 0 1-.267.13a1.5 1.5 0 0 1-.477 0a.43.43 0 0 1-.252-.13c-.194-.19-.371-.503-.463-.99a.39.39 0 0 1 .254-.45");
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.itlfwsb4w {
  stop-color: var(--svg-color--352028, #352028);
  stop-opacity: 0;
}

.iw6o86bel {
  d: path("M15.647 13.783c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.584.845c.664 0 1.248-.338 1.583-.845c.086-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.izufo8bpf {
  fill-rule: evenodd;
  d: path("m13.129 5.882l-.475-1.847v1.847z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jvsy5c46p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.746 27.26h1.797");
}

.jxkioqbgf {
  cx: 13.193px;
  cy: 9.874px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.k43kdziwc {
  d: path("M20.569 12.227c.065-1.064.129-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.k4hskrbnq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.824 28.565h1.797");
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l78-nlbha {
  d: path("M14.278 10.28c0-.288-.235-.48-.298-.538l-.288.279l.177.361z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.liagiztua {
  fill: var(--svg-color--b29aac, #B29AAC);
  d: path("M19.712 21.762a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m22si5bvo {
  d: path("M15.411 3.745h.58v2.137h-.58z");
}

.m6lhrcc1m {
  stop-color: var(--svg-color--e1d7df, #E1D7DF);
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mnbq8nqxg {
  fill: var(--svg-color--e1a474, #E1A474);
  d: path("M26.051 21.18c0-.405.26-.757.568-1.02c.605-.517 1.003-1.392 1.003-2.385c0-1.587-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.288-2.273 2.875c0 .993.398 1.868 1.002 2.385c.309.263.568.615.568 1.02v5.056h1.406z");
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mvu-d8qbf {
  d: path("M19.982 21.617a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.myqq0epvb {
  d: path("M13.46 18.691c.67-.924 1.703-1.194 2.096-1.245c.205.83.308 2.667-.684 3.563c-.635.574-1.078.722-1.67.787c-.163.018-.27-.164-.222-.322c.03-.1.051-.22.053-.365c.01-.634-.108-1.681.426-2.418");
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

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.oc4pkvgaa {
  d: path("m15.264 10.172l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.766 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ongktybvd {
  stop-color: var(--svg-color--a499b2, #A499B2);
  stop-opacity: 0;
}

.ox62rwbrf {
  stop-color: var(--svg-color--e1dbe8, #E1DBE8);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p5552iurb {
  d: path("M8.672 18.007h10.052c2.177 0 3.948 1.796 3.948 4.003v7.997h-14z");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q2qnqo4ln {
  d: path("M10.61 9.688a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.q2rhgqb4s {
  stop-color: var(--svg-color--998ba1, #998BA1);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q6o6udbiy {
  d: path("M23.081 18.362H8.232a10.94 10.94 0 0 1 7.42-2.885c3.484 0 5.153.811 7.43 2.885");
}

.qi731gbjb {
  stop-color: var(--svg-color--282121, #282121);
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qk3h5tshn {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qscu39bls {
  d: path("M10.822 13.651a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.278-4.387.366-6.27c-.011-.767-.657-.772-1.421-.804h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.376.798-3.376 2.665c0 1.86.15 4.405.273 6.27");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r-suar6rb {
  d: path("M20.732 28.137a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rvini-b1k {
  stop-color: var(--svg-color--aa99ac, #AA99AC);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sli_wqbvh {
  stop-color: var(--svg-color--998ba1, #998BA1);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t8nu1bc7r {
  d: path("M20.609 11.576q.057-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.tqc-acwnz {
  fill: var(--svg-color--b5a5c4, #B5A5C4);
  d: path("M20.462 28.282a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.tvis7hbtj {
  d: path("M10.593 9.028a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.ty8nzq04x {
  stop-color: var(--svg-color--373032, #373032);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u7axe2baw {
  stop-color: var(--svg-color--9183a0, #9183A0);
}

.uelaalb7d {
  stop-color: var(--svg-color--da9766, #DA9766);
}

.uf4kgmbxa {
  stop-color: var(--svg-color--271d21, #271D21);
}

.um-bsxb3u {
  cx: 13.193px;
  cy: 9.874px;
  rx: 0.39px;
  ry: 0.197px;
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v5ycnsq6q {
  d: path("M10.785 12.136a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.v68h42b7d {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.256 9.221c-.653 0-1.205.45-1.355 1.059c-.045.175.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.vh02o1b7a {
  stop-color: var(--svg-color--6c5c5a, #6C5C5A);
}

.via-_dbpm {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
}

.vuu318b4c {
  stop-color: var(--svg-color--730620, #730620);
  stop-opacity: 0;
}

.vx2mszbsl {
  fill: var(--svg-color--000, #000);
  d: path("M17.32 10.385c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wixqmvb1w {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.16 10.367l-.634 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.542-.407-.661 0");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wjon1acce {
  d: path("M26.051 21.18c0-.405.26-.757.568-1.02c.605-.517 1.003-1.392 1.003-2.385c0-1.587-1.018-2.875-2.274-2.875c-1.255 0-2.273 1.288-2.273 2.875c0 .993.398 1.868 1.002 2.385c.309.263.568.615.568 1.02v5.056h1.406z");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x_wo803sx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.038 9.221c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.x-c39ztfn {
  d: path("M17.765 9.682c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.326-.135.39-.05");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xrsv2ub3b {
  d: path("M18.626 10.268a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.ygege63ax {
  d: path("M17.855 18.691c-.67-.924-1.704-1.194-2.097-1.245c-.205.83-.308 2.667.684 3.563c.635.574 1.077.722 1.67.787c.163.018.269-.164.221-.322q-.047-.149-.053-.365c-.009-.634.11-1.681-.425-2.418");
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.ylk__q3fj {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.236 8.055a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.ys4clom6y {
  d: path("M10.241 2.092a1.933 1.933 0 0 0-.681 3.743a.215.215 0 0 1 .142.198v1.052c0 .248.202.45.45.45h11.1a.45.45 0 0 0 .45-.45V6.03c0-.089.058-.166.141-.198a1.934 1.934 0 0 0-.69-3.74z");
}

.ysetj63ow {
  stop-color: var(--svg-color--9785a0, #9785A0);
}

.yz1szqxmz {
  d: path("M22.672 30.007h4v-3.502c0-3.421-1.554-6.481-4-8.498z");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z8h9scccv {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M15.652 15.477c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.502c0-3.421-1.554-6.481-4-8.498v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zab3c9ypw {
  stop-color: var(--svg-color--a8a0af, #A8A0AF);
  stop-opacity: 0;
}

.zcwozlblh {
  d: path("M13.463 9.493a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zmama0ttw {
  stop-color: var(--svg-color--46403d, #46403D);
}

.ztvu2mbem {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
}

.zw3ek-w3v {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.264 10.172l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.766 0");
}

.zxda46ott {
  d: path("M19.982 25.247a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
