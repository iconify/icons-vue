<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4RKubc)" class="gjgbc6bfa"/><path fill="url(#iQryzxc)" class="gjgbc6bfa"/><path fill="url(#iWzBopc)" class="gjgbc6bfa"/><path fill="url(#ixaeTFd)" class="gjgbc6bfa"/><path fill="url(#iOidY5d)" class="gjgbc6bfa"/><path fill="url(#iL93Ooc)" class="gjgbc6bfa"/><path fill="url(#iz3Ypye)" class="gjgbc6bfa"/><path fill="url(#iLsm8Sd)" class="l_ac8-bqj"/><path fill="url(#iCnctyd)" class="b0wy21srk"/><path fill="url(#iF7G0Ke)" class="t0sekub4b"/><path fill="url(#iGQ0ldb)" class="t0sekub4b"/><path fill="url(#ijykGbb)" class="t0sekub4b"/><path fill="url(#ijY49Ce)" class="afa0v9x7n"/><path fill="url(#iT6HO5c)" class="afa0v9x7n"/><path fill="url(#iTLD87z)" class="afa0v9x7n"/><path fill="url(#i3v5Hfd)" class="qufb6byjw"/><path fill="url(#inUoghd)" class="qufb6byjw"/><path fill="url(#iLsm8Sd)" class="l_ac8-bqj"/><path fill="url(#iCnctyd)" class="b0wy21srk"/><g filter="url(#iGijlcb)"><path class="mvpk3buav"/></g><g filter="url(#i93YGru)"><path fill="url(#i5caeWd)" class="ryglpfp5i"/></g><path fill="url(#ihYykpN)" class="tlf3acbzt"/><path fill="url(#iDLRIbe)" class="tlf3acbzt"/><path fill="url(#i0kpmTd)" class="tlf3acbzt"/><path fill="url(#iFRXgFb)" class="tlf3acbzt"/><path fill="url(#iZ6ub0b)" class="tlf3acbzt"/><path fill="url(#iSyGtbc)" class="tlf3acbzt"/><path fill="url(#i9GMUSd)" class="xj4rr8bcs"/><path fill="url(#ivMLYOb)" class="xj4rr8bcs"/><path fill="url(#is66ZNS)" class="xj4rr8bcs"/><path fill="url(#iNAmQqe)" class="xj4rr8bcs"/><path fill="url(#i3HHAwe)" class="xj4rr8bcs"/><path fill="url(#i7w92Pe)" class="xj4rr8bcs"/><path fill="url(#i9q1ATd)" class="pq58_nbwh"/><path clip-rule="evenodd" class="xx-8kvbhi"/><path fill="url(#ia8J0bb)" clip-rule="evenodd" class="qk7m0tbun"/><path fill="url(#if85VEd)" clip-rule="evenodd" class="qk7m0tbun"/><path fill="url(#ijetQWb)" clip-rule="evenodd" class="qk7m0tbun"/><path fill="url(#i76lkge)" clip-rule="evenodd" class="qk7m0tbun"/><g filter="url(#iywGKrc)"><path class="q6k6j7beo"/></g><path fill="url(#iXwiz4d)" class="x1oq2zbrx"/><g filter="url(#irMFe5c)"><path fill="url(#ishokLd)" class="gmo2pwb0e"/></g><g filter="url(#iBiMpnb)"><path fill="url(#i1CjK9S)" clip-rule="evenodd" class="gegb8--ce"/></g><g filter="url(#iErIpdc)"><path class="fpjrjzbjn"/></g><path fill="url(#in6Moxd)" clip-rule="evenodd" class="zk4849v5s"/><path fill="url(#i2Bqfud)" clip-rule="evenodd" class="zk4849v5s"/><path fill="url(#iPSBzMe)" clip-rule="evenodd" class="j-mau5bkq"/><path fill="url(#iYlv6pd)" clip-rule="evenodd" class="j-mau5bkq"/><path fill="url(#iGnvtUb)" class="rpb1kgb3j"/><path fill="url(#i5RVRXd)" class="tr7a6plnp"/><g filter="url(#i2y7SRd)"><path fill="url(#icBrkWc)" class="clcrpgbhy"/></g><path fill="url(#i0ce2sc)" class="clcrpgbhy"/><path fill="url(#i6lRgyd)" class="clcrpgbhy"/><path fill="url(#iHVzEac)" class="clcrpgbhy"/><path fill="url(#itWdo8n)" class="clcrpgbhy"/><path fill="url(#iQXDJQd)" class="clcrpgbhy"/><path fill="url(#iRvwBGb)" class="clcrpgbhy"/><path fill="url(#i10Lctb)" class="clcrpgbhy"/><g filter="url(#ilSoUle)"><path class="dbml4nb5h"/></g><g filter="url(#iTfI52b)"><path class="dgj9ybcge"/><path fill="url(#iVQ2LQK)" class="ei4unccsk"/><path fill="url(#iq5f1Vc)" class="ei4unccsk"/><path fill="url(#ilJq1Uy)" class="ei4unccsk"/><path fill="url(#i84OKye)" class="ei4unccsk"/><path fill="url(#i2j6trd)" class="ei4unccsk"/></g><g filter="url(#iFOtaGS)"><path stroke="url(#iRbNWgb)" class="w6gvpsb4o"/></g><path fill="url(#itpeDHK)" class="u71uoebjb"/><g filter="url(#iCHextc)"><path fill="url(#icfZILb)" class="n0mxihbez"/><path fill="url(#ituYNpd)" class="n0mxihbez"/><path fill="url(#i3MGWcd)" class="n0mxihbez"/><path fill="url(#iTbdDYD)" class="n0mxihbez"/><path fill="url(#ifc70ke)" class="n0mxihbez"/></g><g filter="url(#i2VgUhV)"><path class="l8xh99ths"/></g><g filter="url(#i1jG8UP)"><path class="zthskttci"/></g><g filter="url(#i96HuEd)"><path class="gsyns3b4u"/><path fill="url(#injEXPb)" class="hh6pny8es"/><path fill="url(#ikdWdxd)" class="hh6pny8es"/></g><g filter="url(#i9fL9rc)"><path class="pk0dgtmpo"/><path fill="url(#ig2DLrb)" class="h_qj3v0ik"/><path fill="url(#iqv2RFb)" class="h_qj3v0ik"/><path fill="url(#inmzbje)" class="h_qj3v0ik"/></g><path class="f_ftaebei"/><path fill="url(#iv9Ulzn)" class="lf7hbnbei"/><path class="zqnnmc10g"/><g filter="url(#iPICDPd)"><path class="a1uzw0b2q"/><path fill="url(#ijX5nYc)" class="yf6g9lbqm"/></g><g filter="url(#iJCl7wc)"><path fill="url(#ifcpsjd)" class="fejercbkj"/></g><path class="t7mrcybye"/><path fill="url(#itBLZXp)" class="fxovvrb0g"/><path class="jid8f3b4k"/><g filter="url(#i3Z4W2d)"><path fill="url(#iEAuVWN)" class="y9cvw_xsp"/></g><g filter="url(#igBbUee)"><ellipse transform="rotate(-27.914 13.337 9.93)" class="mgp313zrs"/><ellipse fill="url(#ilENSth)" transform="rotate(-27.914 13.337 9.93)" class="jraqvab9j"/></g><path fill="url(#iFjO5Lb)" class="s7ln44bcg"/><path fill="url(#igojIib)" class="s7ln44bcg"/><path fill="url(#i0tcZIc)" class="s7ln44bcg"/><path fill="url(#izDHYcd)" class="s7ln44bcg"/><path fill="url(#iIDMWUb)" class="idmw1cc3p"/><path fill="url(#iwJPAId)" class="idmw1cc3p"/><g filter="url(#iGtuHdd)"><path fill="url(#iehQABe)" class="q39ylwmir"/></g><g filter="url(#iO6fBFs)"><path fill="url(#iSgcBfb)" class="dw8vdrgae"/></g><g filter="url(#iTI5KTB)"><path class="o76uwtp_o"/></g><g filter="url(#iqD9fMe)"><path class="chzak_bxk"/></g><defs><radialGradient id="i4RKubc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.05 23.925)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iOidY5d" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.082 8.22)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iL93Ooc" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.397 23.469)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iz3Ypye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.821 29.993)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iF7G0Ke" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.187 24.706)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iGQ0ldb" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.784 12.279)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="ijY49Ce" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.086 21.956)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iT6HO5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.398 20.33)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="i3v5Hfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 15.855 18.55)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="pmel6eb9u"/><stop offset="1" class="ahs4l-bul"/></radialGradient><radialGradient id="inUoghd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.219 30.487)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rz95hov5a"/><stop offset="1" class="pwmvjmb6w"/></radialGradient><radialGradient id="iFRXgFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 18.994 18.112)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iZ6ub0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.302 26.554)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="iSyGtbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 18.994 24.862)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="i9GMUSd" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.308 11.264)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="ivMLYOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 9.985 24.917)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iNAmQqe" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.156 19.488)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="i3HHAwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 11.953 18.315)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="i7w92Pe" cx="0" cy="0" r="1" gradientTransform="matrix(1.82812 2.125 -.73855 .63537 12.297 21.33)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="i9q1ATd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.84375 3.36136 0 15.84 18.94)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="qyafppwzj"/><stop offset=".857" class="jpwsb7lbg"/></radialGradient><radialGradient id="if85VEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.36 16.378)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="ijetQWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.437 20.034)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="i76lkge" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.746 12.147)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="iXwiz4d" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.083 18.023)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="ishokLd" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.103 25.901)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="i2Bqfud" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 9.985 23.565)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="iGnvtUb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.731 20.705)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i5RVRXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.734 12.374)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="icBrkWc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.598 10.943)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="i6lRgyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.99815 12.76794 -10.57334 -.82659 17.372 5.03)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="www4dfogh"/><stop offset="1" class="c0317ln8x"/></radialGradient><radialGradient id="iHVzEac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.237 9.63)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="itWdo8n" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.49 9.676)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iQXDJQd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.223 11.93)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iRvwBGb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 10.323 6.618)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="i10Lctb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.217 5.964)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iq5f1Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.256 12.303)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i84OKye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.373 11.733)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="itpeDHK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.79 14.482)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ituYNpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.56 8.05)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i3MGWcd" cx="0" cy="0" r="1" gradientTransform="matrix(.11404 -2.51254 4.45173 .20206 20.65 9.36)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iTbdDYD" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.41 -1.436)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="ifc70ke" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 14.885 1.492)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="injEXPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 16.044 3.751)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ikdWdxd" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 10.36 7.693)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ig2DLrb" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 19.204 4.528)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iqv2RFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.424 7.565)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="inmzbje" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -43.5 153.6)scale(3.27032 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iv9Ulzn" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.973 10.027)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ijX5nYc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.348 .71)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itBLZXp" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.608 10.026)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ilENSth" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.322 10.245)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igojIib" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.408 10.04)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="i0tcZIc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.768 10.585)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="izDHYcd" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.882 10.758)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iwJPAId" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.762 5.011)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iehQABe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 10.876 10.683)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><linearGradient id="iQryzxc" x1="23.164" x2="22.852" y1="24.604" y2="24.604" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iWzBopc" x1="8.586" x2="8.922" y1="24.604" y2="24.604" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="ixaeTFd" x1="16.031" x2="16.031" y1="30.956" y2="29.143" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iLsm8Sd" x1="8.67" x2="23.046" y1="15.433" y2="15.433" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iCnctyd" x1="8.67" x2="23.046" y1="15.403" y2="15.403" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ijykGbb" x1="6.85" x2="6.85" y1="30.769" y2="29.309" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iTLD87z" x1="22.521" x2="23.3" y1="25.642" y2="25.642" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="i5caeWd" x1="16.031" x2="23.656" y1="26.987" y2="19.393" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="ihYykpN" x1="21.745" x2="16.63" y1="18.383" y2="23.901" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iDLRIbe" x1="19.899" x2="19.742" y1="15.664" y2="17.726" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="i0kpmTd" x1="17.438" x2="18.594" y1="18.909" y2="19.393" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="is66ZNS" x1="12.125" x2="12.453" y1="23.206" y2="22.847" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="ia8J0bb" x1="20.164" x2="19.492" y1="23.675" y2="23.69" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="i1CjK9S" x1="12.06" x2="12.06" y1="19.873" y2="28.456" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="in6Moxd" x1="9.369" x2="10.264" y1="25.272" y2="25.272" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iPSBzMe" x1="13.742" x2="14.414" y1="25.282" y2="25.282" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iYlv6pd" x1="14.805" x2="14.563" y1="24.8" y2="24.8" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="i0ce2sc" x1="20.947" x2="16.595" y1="12.628" y2="12.628" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iVQ2LQK" x1="16.628" x2="15.79" y1="11.617" y2="11.652" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="ilJq1Uy" x1="15.79" x2="15.79" y1="12.756" y2="12.291" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i2j6trd" x1="15.79" x2="15.79" y1="9.922" y2="10.598" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iRbNWgb" x1="14.588" x2="14.907" y1="14.328" y2="13.493" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="icfZILb" x1="22.642" x2="11.03" y1="5.28" y2="5.28" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ifcpsjd" x1="18.75" x2="18.436" y1="10.08" y2="10.273" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEAuVWN" x1="14.352" x2="14.038" y1="10.08" y2="10.274" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFjO5Lb" x1="22.226" x2="21.02" y1="10.107" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iIDMWUb" x1="9.94" x2="11.399" y1="10.811" y2="10.684" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iSgcBfb" x1="21.269" x2="21.269" y1="9.736" y2="11.64" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><filter id="iGijlcb" width="7.147" height="11.557" x="8.885" y="15.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".5"/></filter><filter id="i93YGru" width="7.147" height="11.557" x="15.779" y="15.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".5"/></filter><filter id="iywGKrc" width="3.699" height="3.699" x="16.85" y="24.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".375"/></filter><filter id="irMFe5c" width="1.42" height="1.42" x="18.82" y="24.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/></filter><filter id="iBiMpnb" width="5.381" height="7.171" x="9.369" y="19.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/></filter><filter id="iErIpdc" width="5.3" height="6.89" x="9.435" y="19.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".15"/></filter><filter id="i2y7SRd" width="11.22" height="12.542" x="10.727" y="4.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24156" result="effect2_innerShadow_3987_24156"/></filter><filter id="ilSoUle" width="3.747" height="4.9" x="13.775" y="9.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".5"/></filter><filter id="iTfI52b" width="2.277" height="3.3" x="14.651" y="9.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".1"/></filter><filter id="iFOtaGS" width="3.718" height="1.573" x="13.931" y="13.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".05"/></filter><filter id="iCHextc" width="12.873" height="8.356" x="9.354" y="1.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24156" result="effect2_innerShadow_3987_24156"/></filter><filter id="i2VgUhV" width="2.339" height="1.19" x="17.379" y="7.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/></filter><filter id="i1jG8UP" width="2.339" height="1.176" x="12.123" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/></filter><filter id="i96HuEd" width="6.734" height="5.992" x="9.709" y="2.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24156"/><feGaussianBlur result="effect2_foregroundBlur_3987_24156" stdDeviation=".125"/></filter><filter id="i9fL9rc" width="6.361" height="5.736" x="15.631" y="3.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".125"/></filter><filter id="iPICDPd" width=".787" height=".696" x="17.238" y="9.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".05"/></filter><filter id="iJCl7wc" width=".891" height=".913" x="18.078" y="9.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".1"/></filter><filter id="i3Z4W2d" width=".986" height="1.04" x="13.635" y="9.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".1"/></filter><filter id="igBbUee" width=".913" height=".704" x="12.88" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".05"/></filter><filter id="iGtuHdd" width="1.329" height="2.379" x="9.709" y="9.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".125"/></filter><filter id="iO6fBFs" width="1.947" height="2.903" x="20.296" y="9.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".25"/></filter><filter id="iTI5KTB" width="2.405" height="1.16" x="12.042" y="7.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".125"/></filter><filter id="iqD9fMe" width="2.405" height="1.16" x="17.321" y="7.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24156" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:health-worker-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a1uzw0b2q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.909 9.738c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.afa0v9x7n {
  d: path("M26.681 27.963c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ahs4l-bul {
  stop-color: var(--svg-color--b04418, #B04418);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b0wy21srk {
  d: path("M15.88 15.403h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
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

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.chzak_bxk {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.351 8.087c-.257-.184-.898-.508-1.655-.38");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clcrpgbhy {
  d: path("M10.965 13.708a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.dbml4nb5h {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.389 10.419l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.408-.504-.408-.615 0");
}

.dgj9ybcge {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.408 10.228l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dw8vdrgae {
  d: path("M20.796 11.64q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.ei4unccsk {
  d: path("m15.408 10.228l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_ftaebei {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.18 9.277c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fejercbkj {
  d: path("M18.77 10.324a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fpjrjzbjn {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.046 26.287h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
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

.fxovvrb0g {
  d: path("M13.606 9.55a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gegb8--ce {
  fill-rule: evenodd;
  d: path("M12.06 20.854c-.94 0-1.71.762-1.71 1.71v3.299h.67a.49.49 0 0 1 0 .981h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 1 1 0-.981h.6v-3.3a1.71 1.71 0 0 0-1.71-1.709");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gjgbc6bfa {
  d: path("M15.841 15.403c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.gmo2pwb0e {
  d: path("M19.53 26.173a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.gsyns3b4u {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.022 5.327l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96a2.4 2.4 0 0 0 .331-.252l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.807.42.807.892v1.485z");
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h_qj3v0ik {
  d: path("m21.003 8.594l-.03-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.051c1.744 1.138 1.439 3.189.52 4.155");
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hh6pny8es {
  d: path("m16.022 5.327l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96a2.4 2.4 0 0 0 .331-.252l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.807.42.807.892v1.485z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.idmw1cc3p {
  d: path("M10.746 9.084a1.62 1.62 0 0 0-1.392 1.593c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.2");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j-mau5bkq {
  fill-rule: evenodd;
  d: path("M14.75 23.724v2.47c0 .36-.289.65-.65.65h-.58v-.981h.25v-2.14z");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jid8f3b4k {
  fill: var(--svg-color--000, #000);
  d: path("M14.117 10.442a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.jpwsb7lbg {
  stop-color: var(--svg-color--995e4c, #995E4C);
}

.jraqvab9j {
  cx: 13.337px;
  cy: 9.931px;
  rx: 0.39px;
  ry: 0.197px;
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

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l_ac8-bqj {
  d: path("M16.21 15.403c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.l8xh99ths {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.523 7.963a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 0 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.lf7hbnbei {
  d: path("M17.974 9.55a.893.893 0 0 1 .86 1.127H17.11a.896.896 0 0 1 .864-1.128");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgp313zrs {
  cx: 13.337px;
  cy: 9.931px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.mvpk3buav {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.062 20.147l.732.13a.213.213 0 0 1 .12.353l-.704.77a.216.216 0 0 0 .01.296l4.505 4.599c.111.11.306.037.306-.12v-3.33c0-.037-.01-.064-.018-.101l-2.54-5.888a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.003a.214.214 0 0 0 .177.231");
}

.n0mxihbez {
  d: path("M20.645 4.3c.514.177.976.536 1.267 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874V9.94a1.75 1.75 0 0 0-.667-.269l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.299-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.581.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o76uwtp_o {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.417 8.133c.257-.184.897-.508 1.655-.381");
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
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

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pk0dgtmpo {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.003 8.594l-.03-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.051c1.744 1.138 1.439 3.189.52 4.155");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmel6eb9u {
  stop-color: var(--svg-color--e56e23, #E56E23);
}

.pq58_nbwh {
  d: path("M15.84 18.713a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pwmvjmb6w {
  stop-color: var(--svg-color--e35628, #E35628);
  stop-opacity: 0;
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q39ylwmir {
  d: path("M10.705 9.744a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q6k6j7beo {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.7 26.952a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qk7m0tbun {
  fill-rule: evenodd;
  d: path("M15.79 15.114a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.qufb6byjw {
  d: path("M16.348 22.508c0-.04-.01-.204 0-.244l2.662-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.055.05.055.09l.055 3.6h.01v3.97h.79v-3.97l.078-3.416z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyafppwzj {
  stop-color: var(--svg-color--bf887f, #BF887F);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rpb1kgb3j {
  d: path("M20.651 12.192c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.ryglpfp5i {
  d: path("m21.748 20.147l-.732.13a.213.213 0 0 0-.12.353l.704.77a.216.216 0 0 1-.01.296l-4.505 4.599c-.112.11-.306.037-.306-.12v-3.33c0-.037.009-.064.018-.101l2.54-5.888a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.185 2.003a.214.214 0 0 1-.176.231");
}

.rz95hov5a {
  stop-color: var(--svg-color--e35628, #E35628);
}

.s7ln44bcg {
  d: path("M20.712 12.284q.101-1.597.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0sekub4b {
  d: path("m5.78 22.764l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.t7mrcybye {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.399 9.277c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.tlf3acbzt {
  d: path("M16.504 21.685c-.262.515-.262.941-.262 1.305v2.992c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.06a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.426-1.134a.3.3 0 0 0-.04.08z");
}

.tr7a6plnp {
  d: path("M10.929 12.192a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.u71uoebjb {
  d: path("M15.79 13.84c-.507 0-.984-.12-1.385-.33c-.137-.069-.285.085-.198.21c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
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

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w6gvpsb4o {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.44 13.444h-.002a.23.23 0 0 0-.27.047a.21.21 0 0 0-.023.27c.348.529.955.88 1.645.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x1oq2zbrx {
  d: path("M19.53 26.724a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xj4rr8bcs {
  d: path("M15.225 21.685c.263.515.263.941.263 1.305v2.992c0 .17-.209.26-.328.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.06a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xx-8kvbhi {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.79 15.114a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.y9cvw_xsp {
  d: path("M14.421 10.337c0-.288-.234-.48-.297-.539l-.289.28l.178.36z");
}

.yf6g9lbqm {
  d: path("M17.909 9.738c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
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

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zk4849v5s {
  fill-rule: evenodd;
  d: path("M9.37 26.183v-2.47h.98v2.14h.25v.981h-.58a.65.65 0 0 1-.65-.65");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zqnnmc10g {
  fill: var(--svg-color--000, #000);
  d: path("M17.463 10.442c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.zthskttci {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.38 7.854a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.439z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
