<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7lwmee)" class="ajdcnfjbq"/><rect transform="rotate(39.69 8.209 20.466)" class="j91r45jxl"/><rect fill="url(#iOzS2gc)" transform="rotate(39.69 8.209 20.466)" class="umyf4mutz"/><rect transform="rotate(39.148 7.506 15.512)" class="m2vf_qbgh"/><path class="lagjvcqfq"/><path fill="url(#iX831Ke)" class="rqx9m1l-q"/><path class="ibpw20b6z"/><path fill="url(#ifLZwjc)" class="qpb9ax0zw"/><path class="ye20c1b5m"/><path class="krd91cd0k"/><path fill="url(#i7GuTBd)" class="hfd2aq14h"/><path class="b6l-hhbxi"/><path fill="url(#iOVY4yc)" class="ibx37wn8q"/><path class="x1wf31bst"/><path fill="url(#iMcYJgc)" class="lv_qevbag"/><path class="zl01-1bby"/><path fill="url(#isqJtni)" class="lbqxn0p5l"/><path class="nl5bzvbef"/><path fill="url(#iChqswF)" class="ok8qifa1z"/><path class="ptqpcubpm"/><path fill="url(#imaDERb)" class="l6bu4j-yt"/><path class="qy_aqj7tt"/><path fill="url(#if4qjxe)" class="e0ihpyb6a"/><path class="ftfib_bqb"/><path fill="url(#i7RaX3d)" class="orsyj282y"/><rect transform="rotate(39.148 25.408 3.36)" class="vsu7wrh5b"/><rect fill="url(#iXMPqme)" transform="rotate(39.148 25.408 3.36)" class="szx1ozbvj"/><path class="x46fe_njv"/><path fill="url(#iZoqeIe)" class="idkhqx73r"/><rect transform="rotate(39.148 24.167 2.328)" class="xemu2llat"/><rect fill="url(#iJwxgye)" transform="rotate(39.148 24.167 2.328)" class="rep155avo"/><g filter="url(#iuG6uUb)"><path fill="url(#iOu3I1c)" class="pp-i1x44e"/></g><g filter="url(#iQaCf0c)"><path fill="url(#iSTkxgr)" class="gsqtc_b1i"/></g><g filter="url(#ieG2PxE)"><path fill="url(#iEaeIub)" class="a4y-9vzcr"/></g><g filter="url(#iuDDYMg)"><path fill="url(#iL8x66d)" class="jtiov1buy"/></g><path class="d_52ybblq"/><path fill="url(#ixSbK8b)" class="ew16hc4zm"/><path fill="url(#i8v8pBd)" class="ew16hc4zm"/><g filter="url(#iatQUzK)"><path fill="url(#i5rCTKK)" class="c5tk5fbib"/></g><path fill="url(#ixvlFnD)" class="ap76ugb_r"/><path fill="url(#iiRL8ee)" class="ap76ugb_r"/><path fill="url(#iRk8Tjd)" class="ap76ugb_r"/><path fill="url(#iNpXVJb)" class="ap76ugb_r"/><g filter="url(#i7mEz1H)"><path fill="url(#icVUhAe)" class="r30y-n13x"/></g><defs><radialGradient id="iOzS2gc" cx="0" cy="0" r="1" gradientTransform="rotate(161.622 5.41 14.261)scale(6.10496 4.02993)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="pkd4vi1ry"/><stop offset=".543" class="bjtka8ehe"/><stop offset="1" class="zn8-94zmi"/></radialGradient><radialGradient id="iX831Ke" cx="0" cy="0" r="1" gradientTransform="matrix(.59373 5.34376 -7.36519 .81833 10.532 12.781)" gradientUnits="userSpaceOnUse"><stop class="ymkt5ma4v"/><stop offset=".732" class="bbmz8hqyo"/><stop offset=".915" class="sqhd34bst"/></radialGradient><radialGradient id="i7GuTBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 4.625 -6.43788 -.0435 19.063 4)" gradientUnits="userSpaceOnUse"><stop class="ytj2zukoj"/><stop offset="1" class="jypsqkbiz"/></radialGradient><radialGradient id="iOVY4yc" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 4.4375 -6.12074 .21552 14.531 8.375)" gradientUnits="userSpaceOnUse"><stop class="ymkt5ma4v"/><stop offset="1" class="jypsqkbiz"/></radialGradient><radialGradient id="iMcYJgc" cx="0" cy="0" r="1" gradientTransform="rotate(154.455 12.553 8.398)scale(4.71046 5.38951)" gradientUnits="userSpaceOnUse"><stop class="mrh1odovy"/><stop offset="1" class="d6yzfvbko"/></radialGradient><radialGradient id="isqJtni" cx="0" cy="0" r="1" gradientTransform="rotate(133.783 8.483 12.929)scale(4.51634 6.07486)" gradientUnits="userSpaceOnUse"><stop class="b639h979y"/><stop offset=".877" class="d6yzfvbko"/></radialGradient><radialGradient id="i7RaX3d" cx="0" cy="0" r="1" gradientTransform="rotate(100.421 10.633 11)scale(2.76434 3.75305)" gradientUnits="userSpaceOnUse"><stop class="ytj2zukoj"/><stop offset="1" class="jypsqkbiz"/></radialGradient><radialGradient id="iXMPqme" cx="0" cy="0" r="1" gradientTransform="matrix(-.84266 2.03385 -2.91957 -1.20962 28.84 4.114)" gradientUnits="userSpaceOnUse"><stop class="rxxbd_sdt"/><stop offset="1" class="d6yzfvbko"/></radialGradient><radialGradient id="iZoqeIe" cx="0" cy="0" r="1" gradientTransform="rotate(155.4 13.443 4.633)scale(2.85266 2.92947)" gradientUnits="userSpaceOnUse"><stop class="qaadn3b5g"/><stop offset=".924" class="c3eqj1b3l"/></radialGradient><radialGradient id="ixSbK8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 10.49995 -3.47431 -.1034 8.188 13.063)" gradientUnits="userSpaceOnUse"><stop offset=".037" class="dy4a6-3mn"/><stop offset="1" class="e2nfkmbsh"/></radialGradient><radialGradient id="i8v8pBd" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 5.75 -4.6394 3.17699 3.625 23.375)" gradientUnits="userSpaceOnUse"><stop class="x8py3pbjr"/><stop offset="1" class="yfym2sbuf"/></radialGradient><radialGradient id="iiRL8ee" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 8.5625 -11.95084 -1.04678 12.688 29.625)" gradientUnits="userSpaceOnUse"><stop class="wacdh8bcg"/><stop offset="1" class="gv1ccmb3u"/></radialGradient><radialGradient id="iRk8Tjd" cx="0" cy="0" r="1" gradientTransform="matrix(.75 4.3125 -11.36018 1.97568 20.063 21.5)" gradientUnits="userSpaceOnUse"><stop class="xsc7nr64m"/><stop offset="1" class="su6h_n-dx"/></radialGradient><radialGradient id="iNpXVJb" cx="0" cy="0" r="1" gradientTransform="matrix(2 5.125 -9.69307 3.78266 21.75 27.313)" gradientUnits="userSpaceOnUse"><stop class="mpe_0unzy"/><stop offset=".852" class="rlsfniicc"/></radialGradient><linearGradient id="i7lwmee" x1="15.618" x2="14.096" y1="25.745" y2="20.188" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset=".863" class="h66atab_c"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="ifLZwjc" x1="12.813" x2="8.975" y1="19.375" y2="24.518" gradientUnits="userSpaceOnUse"><stop offset=".042" class="onffjjbxd"/><stop offset=".142" class="mkrdo-tll"/><stop offset=".433" class="t3sj_d8-p"/><stop offset=".645" class="sldm7lbgt"/></linearGradient><linearGradient id="iChqswF" x1="17.625" x2="12.642" y1="13.188" y2="19.724" gradientUnits="userSpaceOnUse"><stop class="cbflu-bat"/><stop offset=".548" class="iiilc2bxy"/><stop offset="1" class="sldm7lbgt"/></linearGradient><linearGradient id="imaDERb" x1="21.75" x2="15.492" y1="8.313" y2="16.369" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cbflu-bat"/><stop offset=".468" class="iiilc2bxy"/><stop offset=".821" class="i3mdpdbqo"/><stop offset="1" class="sldm7lbgt"/></linearGradient><linearGradient id="if4qjxe" x1="25.28" x2="19.302" y1="4.087" y2="11.766" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cbflu-bat"/><stop offset=".468" class="iiilc2bxy"/><stop offset=".821" class="i3mdpdbqo"/><stop offset="1" class="sldm7lbgt"/></linearGradient><linearGradient id="iJwxgye" x1="26.279" x2="26.431" y1=".903" y2="6.479" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cbflu-bat"/><stop offset=".468" class="iiilc2bxy"/><stop offset=".821" class="i3mdpdbqo"/><stop offset="1" class="sldm7lbgt"/></linearGradient><linearGradient id="iOu3I1c" x1="16.982" x2="12.465" y1="17.29" y2="14.002" gradientUnits="userSpaceOnUse"><stop class="mler9swlk"/><stop offset=".471" class="nijrl5vvw"/><stop offset="1" class="fw1u_f1mo"/></linearGradient><linearGradient id="iSTkxgr" x1="20.725" x2="16.208" y1="12.798" y2="9.511" gradientUnits="userSpaceOnUse"><stop class="mler9swlk"/><stop offset=".471" class="nijrl5vvw"/><stop offset="1" class="fw1u_f1mo"/></linearGradient><linearGradient id="iEaeIub" x1="24.391" x2="19.895" y1="8.314" y2="5.312" gradientUnits="userSpaceOnUse"><stop class="mler9swlk"/><stop offset=".471" class="nijrl5vvw"/><stop offset="1" class="fw1u_f1mo"/></linearGradient><linearGradient id="iL8x66d" x1="25.9" x2="24.046" y1="4.704" y2="3.421" gradientUnits="userSpaceOnUse"><stop class="mler9swlk"/><stop offset=".471" class="nijrl5vvw"/><stop offset="1" class="fw1u_f1mo"/></linearGradient><linearGradient id="i5rCTKK" x1="8.024" x2="9.377" y1="11.422" y2="23.721" gradientUnits="userSpaceOnUse"><stop class="wer4cjcas"/><stop offset=".352" class="gv56f9bpy"/><stop offset="1" class="bp-glubwr"/></linearGradient><linearGradient id="ixvlFnD" x1="2.063" x2="26.563" y1="23.125" y2="22.813" gradientUnits="userSpaceOnUse"><stop offset=".11" class="iw3a8n0br"/><stop offset=".582" class="gctigdbfe"/><stop offset="1" class="znrgouaxn"/></linearGradient><linearGradient id="icVUhAe" x1="26.084" x2="15.141" y1="22.375" y2="23.088" gradientUnits="userSpaceOnUse"><stop class="naukbeb2q"/><stop offset=".52" class="wr9fq-bhm"/><stop offset="1" class="bln6kif6x"/></linearGradient><filter id="iuG6uUb" width="8.375" height="7.423" x="11.002" y="12.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31130" stdDeviation=".5"/></filter><filter id="iQaCf0c" width="8.375" height="7.423" x="14.745" y="8.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31130" stdDeviation=".5"/></filter><filter id="ieG2PxE" width="8.334" height="7.077" x="18.442" y="4.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31130" stdDeviation=".5"/></filter><filter id="iuDDYMg" width="4.973" height="4.561" x="22.588" y="2.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31130" stdDeviation=".5"/></filter><filter id="iatQUzK" width="5.174" height="14.835" x="4.644" y="10.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31130" stdDeviation=".25"/></filter><filter id="i7mEz1H" width="14.487" height="4.817" x="12.997" y="20.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31130" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-of-corn" /></template>
<style>
.a4y-9vzcr {
  d: path("M20.844 5.075c.772.1 4.454 3.014 4.794 3.434s-.058 1.632-.058 1.632l-6.138-4.533s.63-.633 1.402-.533");
}

.ajdcnfjbq {
  d: path("m12.159 23.92l2.43 1.38c.82.47 1.84.37 2.55-.25c.38-.33.64-.78.73-1.28c.17-.93-.27-1.86-1.08-2.33l-2.43-1.38");
}

.ap76ugb_r {
  d: path("M26.938 22.766c-.012-1.786-7.579-6.5-12.641-3.782c-5.063 2.72-9.326 4.17-9.203 5.328c.29 2.746 7.937 6.516 12.89 3.547s8.965-3.308 8.953-5.093");
}

.b639h979y {
  stop-color: var(--svg-color--ffe352, #FFE352);
}

.b6l-hhbxi {
  fill: var(--svg-color--c07f00, #C07F00);
  d: path("M12.548 7.84a2.93 2.93 0 0 1 4.126-.422l2.951 2.403a2.93 2.93 0 0 1 .423 4.125l-.158.194a2.93 2.93 0 0 1-4.125.423l-2.952-2.403a2.933 2.933 0 0 1-.423-4.125z");
}

.bbmz8hqyo {
  stop-color: var(--svg-color--925600, #925600);
}

.bjtka8ehe {
  stop-color: var(--svg-color--1c6d4c, #1C6D4C);
}

.bln6kif6x {
  stop-color: var(--svg-color--58ca59, #58CA59);
  stop-opacity: 0.32;
}

.bp-glubwr {
  stop-color: var(--svg-color--146444, #146444);
}

.c3eqj1b3l {
  stop-color: var(--svg-color--ffeb56, #FFEB56);
  stop-opacity: 0;
}

.c5tk5fbib {
  d: path("M5.144 24.746c4.708-4.565 4.906-11.342 3.176-13.834c.123 3.48-.02 4.998-.4 6.867c-.47 2.306-2.776 6.967-2.776 6.967");
}

.cbflu-bat {
  stop-color: var(--svg-color--f0b301, #F0B301);
}

.d_52ybblq {
  fill: var(--svg-color--1b7c1e, #1B7C1E);
  d: path("M8.25 10.5c-1.016-.078-1.29 1.42-2.984 4.516s-2 7.968 1.048 11.037l2.358-3.881c2.906-5.14.594-11.594-.422-11.672");
}

.d6yzfvbko {
  stop-color: var(--svg-color--ffe558, #FFE558);
  stop-opacity: 0;
}

.dy4a6-3mn {
  stop-color: var(--svg-color--20cc21, #20CC21);
}

.e0ihpyb6a {
  d: path("M18.343 5.325a2.854 2.854 0 0 1 4.016-.411l3.073 2.501a2.854 2.854 0 0 1-3.604 4.427l-3.073-2.501a2.854 2.854 0 0 1-.412-4.016");
}

.e2nfkmbsh {
  stop-color: var(--svg-color--56c857, #56C857);
  stop-opacity: 0;
}

.ew16hc4zm {
  d: path("M8.25 10.5c-1.016-.078-1.29 1.42-2.984 4.516s-2 7.968 1.048 11.037l2.358-3.881c2.906-5.14.594-11.594-.422-11.672");
}

.ft5dv1b6b {
  fill: none;
}

.ftfib_bqb {
  fill: var(--svg-color--d98d00, #D98D00);
  d: path("M22 2.675c.57-.7 1.601-.806 2.302-.236l.908.739a1.636 1.636 0 1 1-2.066 2.538l-.908-.74a1.636 1.636 0 0 1-.236-2.3");
}

.fw1u_f1mo {
  stop-color: var(--svg-color--ffd856, #FFD856);
  stop-opacity: 0;
}

.gctigdbfe {
  stop-color: var(--svg-color--1fb720, #1FB720);
}

.gsqtc_b1i {
  d: path("M17.19 9.315c.786.146 4.466 3.309 4.803 3.753s-.102 1.647-.102 1.647l-6.146-4.943s.66-.602 1.446-.457");
}

.gv1ccmb3u {
  stop-color: var(--svg-color--187350, #187350);
  stop-opacity: 0;
}

.gv56f9bpy {
  stop-color: var(--svg-color--56c957, #56C957);
}

.h66atab_c {
  stop-color: var(--svg-color--f89c20, #F89C20);
}

.hfd2aq14h {
  d: path("M16.917 4.124a2.836 2.836 0 0 1 3.99-.409l3.101 2.524a2.836 2.836 0 0 1-3.581 4.4l-3.101-2.524a2.836 2.836 0 0 1-.409-3.99");
}

.i3mdpdbqo {
  stop-color: var(--svg-color--e5a906, #E5A906);
}

.ibpw20b6z {
  fill: var(--svg-color--cba21c, #CBA21C);
  d: path("M6.951 18.872a2.93 2.93 0 0 1 4.126-.423l3.34 2.719a2.933 2.933 0 0 1-3.703 4.548l-3.34-2.718a2.93 2.93 0 0 1-.423-4.126");
}

.ibx37wn8q {
  d: path("M12.548 7.84a2.93 2.93 0 0 1 4.126-.422l2.951 2.403a2.93 2.93 0 0 1 .423 4.125l-.158.194a2.93 2.93 0 0 1-4.125.423l-2.952-2.403a2.933 2.933 0 0 1-.423-4.125z");
}

.idkhqx73r {
  d: path("M28.078 4.072c0 .439-.138.845-.374 1.178c-2.079.984-3.79-.242-3.141-2.585a2.04 2.04 0 0 1 3.515 1.407");
}

.iiilc2bxy {
  stop-color: var(--svg-color--fbcb34, #FBCB34);
}

.iw3a8n0br {
  stop-color: var(--svg-color--256c27, #256C27);
}

.j91r45jxl {
  width: 5.967px;
  height: 9.039px;
  x: 8.209px;
  y: 20.466px;
  fill: var(--svg-color--226523, #226523);
  rx: 2.983px;
}

.jtiov1buy {
  d: path("M24.533 3.199c.397-.063 1.89 1.21 2.003 1.425s-.198 1.133-.198 1.133l-2.75-2.078s.549-.418.945-.48");
}

.jypsqkbiz {
  stop-color: var(--svg-color--f6c130, #F6C130);
  stop-opacity: 0;
}

.krd91cd0k {
  fill: var(--svg-color--c68401, #C68401);
  d: path("M16.917 4.124a2.836 2.836 0 0 1 3.99-.409l3.101 2.524a2.836 2.836 0 0 1-3.581 4.4l-3.101-2.524a2.836 2.836 0 0 1-.409-3.99");
}

.l6bu4j-yt {
  d: path("M14.688 9.705a2.93 2.93 0 0 1 4.125-.423l2.952 2.403a2.93 2.93 0 0 1 .423 4.125l-.075.093a2.933 2.933 0 0 1-4.126.423l-2.952-2.403a2.93 2.93 0 0 1-.422-4.126z");
}

.lagjvcqfq {
  fill: var(--svg-color--c07f00, #C07F00);
  d: path("M8.77 12.423A2.93 2.93 0 0 1 12.894 12l3.025 2.463a2.93 2.93 0 0 1 .423 4.125l-.214.263a2.933 2.933 0 0 1-4.125.423L8.978 16.81a2.93 2.93 0 0 1-.422-4.126z");
}

.lbqxn0p5l {
  d: path("M17.113 11.731a2.93 2.93 0 0 1 4.126-.423l2.965 2.414a2.93 2.93 0 0 1 .423 4.126l-.066.081a2.93 2.93 0 0 1-4.126.423l-2.965-2.414a2.933 2.933 0 0 1-.423-4.125z");
}

.lr_grnbee {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
}

.lv_qevbag {
  d: path("M20.098 6.81a2.854 2.854 0 0 1 4.015-.412L27.186 8.9a2.854 2.854 0 0 1-3.604 4.427l-3.073-2.502a2.854 2.854 0 0 1-.411-4.015");
}

.m2vf_qbgh {
  width: 10.171px;
  height: 5.865px;
  x: 7.506px;
  y: 15.512px;
  fill: var(--svg-color--985b00, #985B00);
  rx: 2.932px;
}

.mkrdo-tll {
  stop-color: var(--svg-color--cf9f00, #CF9F00);
}

.mler9swlk {
  stop-color: var(--svg-color--ffe458, #FFE458);
}

.mpe_0unzy {
  stop-color: var(--svg-color--248f4a, #248F4A);
}

.mrh1odovy {
  stop-color: var(--svg-color--ffed56, #FFED56);
}

.naukbeb2q {
  stop-color: var(--svg-color--57c958, #57C958);
}

.nijrl5vvw {
  stop-color: var(--svg-color--ffda57, #FFDA57);
}

.nl5bzvbef {
  fill: var(--svg-color--cba21c, #CBA21C);
  d: path("M10.88 14.202a2.93 2.93 0 0 1 4.125-.423l2.979 2.425a2.93 2.93 0 0 1 .423 4.125l-.15.184a2.933 2.933 0 0 1-4.125.423l-2.98-2.425a2.93 2.93 0 0 1-.422-4.125z");
}

.ok8qifa1z {
  d: path("M10.88 14.202a2.93 2.93 0 0 1 4.125-.423l2.979 2.425a2.93 2.93 0 0 1 .423 4.125l-.15.184a2.933 2.933 0 0 1-4.125.423l-2.98-2.425a2.93 2.93 0 0 1-.422-4.125z");
}

.onffjjbxd {
  stop-color: var(--svg-color--b17600, #B17600);
}

.orsyj282y {
  d: path("M22 2.675c.57-.7 1.601-.806 2.302-.236l.908.739a1.636 1.636 0 1 1-2.066 2.538l-.908-.74a1.636 1.636 0 0 1-.236-2.3");
}

.pkd4vi1ry {
  stop-color: var(--svg-color--467f82, #467F82);
}

.pp-i1x44e {
  d: path("M13.448 13.807c.784.146 4.465 3.309 4.802 3.753s-.103 1.647-.103 1.647l-6.145-4.943s.66-.603 1.446-.457");
}

.ptqpcubpm {
  fill: var(--svg-color--cba21c, #CBA21C);
  d: path("M14.688 9.705a2.93 2.93 0 0 1 4.125-.423l2.952 2.403a2.93 2.93 0 0 1 .423 4.125l-.075.093a2.933 2.933 0 0 1-4.126.423l-2.952-2.403a2.93 2.93 0 0 1-.422-4.126z");
}

.qaadn3b5g {
  stop-color: var(--svg-color--ffea55, #FFEA55);
}

.qpb9ax0zw {
  d: path("M6.951 18.872a2.93 2.93 0 0 1 4.126-.423l3.34 2.719a2.933 2.933 0 0 1-3.703 4.548l-3.34-2.718a2.93 2.93 0 0 1-.423-4.126");
}

.qy_aqj7tt {
  fill: var(--svg-color--cba21c, #CBA21C);
  d: path("M18.343 5.325a2.854 2.854 0 0 1 4.016-.411l3.073 2.501a2.854 2.854 0 0 1-3.604 4.427l-3.073-2.501a2.854 2.854 0 0 1-.412-4.016");
}

.r30y-n13x {
  d: path("M20.344 21.563c2.937-.22 4.938.593 6.14 1.093c-5.541 0-9.015.969-11.817 1.657c-1.077.264-.624-1.247-.233-1.47c.623-.353 2.972-1.062 5.91-1.28");
}

.rep155avo {
  width: 4.443px;
  height: 3.272px;
  x: 24.167px;
  y: 2.328px;
  rx: 1.636px;
}

.rlsfniicc {
  stop-color: var(--svg-color--26904d, #26904D);
  stop-opacity: 0;
}

.rqx9m1l-q {
  d: path("M8.77 12.423A2.93 2.93 0 0 1 12.894 12l3.025 2.463a2.93 2.93 0 0 1 .423 4.125l-.214.263a2.933 2.933 0 0 1-4.125.423L8.978 16.81a2.93 2.93 0 0 1-.422-4.126z");
}

.rxxbd_sdt {
  stop-color: var(--svg-color--ffe558, #FFE558);
}

.sldm7lbgt {
  stop-color: var(--svg-color--c49002, #C49002);
}

.sqhd34bst {
  stop-color: var(--svg-color--955800, #955800);
}

.su6h_n-dx {
  stop-color: var(--svg-color--26c025, #26C025);
  stop-opacity: 0;
}

.szx1ozbvj {
  width: 4.697px;
  height: 3.272px;
  x: 25.408px;
  y: 3.359px;
  rx: 1.636px;
}

.t3sj_d8-p {
  stop-color: var(--svg-color--dfbe48, #DFBE48);
}

.umyf4mutz {
  width: 5.967px;
  height: 9.039px;
  x: 8.209px;
  y: 20.466px;
  rx: 2.983px;
}

.vsu7wrh5b {
  width: 4.697px;
  height: 3.272px;
  x: 25.408px;
  y: 3.359px;
  fill: var(--svg-color--f7a001, #F7A001);
  rx: 1.636px;
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.wacdh8bcg {
  stop-color: var(--svg-color--175b51, #175B51);
}

.wer4cjcas {
  stop-color: var(--svg-color--59d159, #59D159);
}

.wr9fq-bhm {
  stop-color: var(--svg-color--59ca5a, #59CA5A);
}

.x1wf31bst {
  fill: var(--svg-color--e29300, #E29300);
  d: path("M20.098 6.81a2.854 2.854 0 0 1 4.015-.412L27.186 8.9a2.854 2.854 0 0 1-3.604 4.427l-3.073-2.502a2.854 2.854 0 0 1-.411-4.015");
}

.x46fe_njv {
  fill: var(--svg-color--f3bb30, #F3BB30);
  d: path("M28.078 4.072c0 .439-.138.845-.374 1.178c-2.079.984-3.79-.242-3.141-2.585a2.04 2.04 0 0 1 3.515 1.407");
}

.x8py3pbjr {
  stop-color: var(--svg-color--145637, #145637);
}

.xemu2llat {
  width: 4.443px;
  height: 3.272px;
  x: 24.167px;
  y: 2.328px;
  fill: var(--svg-color--cba21c, #CBA21C);
  rx: 1.636px;
}

.xsc7nr64m {
  stop-color: var(--svg-color--2ac127, #2AC127);
}

.ye20c1b5m {
  fill: var(--svg-color--dfbb38, #DFBB38);
  d: path("M13.551 16.35a2.933 2.933 0 0 1 4.126-.423l2.979 2.425a2.93 2.93 0 0 1 .422 4.126l-.15.183a2.93 2.93 0 0 1-4.125.423l-2.979-2.424a2.93 2.93 0 0 1-.422-4.126z");
}

.yfym2sbuf {
  stop-color: var(--svg-color--1c5a2d, #1C5A2D);
  stop-opacity: 0;
}

.ymkt5ma4v {
  stop-color: var(--svg-color--f0bf2c, #F0BF2C);
}

.ytj2zukoj {
  stop-color: var(--svg-color--fcc62f, #FCC62F);
}

.zl01-1bby {
  fill: var(--svg-color--e29300, #E29300);
  d: path("M17.113 11.731a2.93 2.93 0 0 1 4.126-.423l2.965 2.414a2.93 2.93 0 0 1 .423 4.126l-.066.081a2.93 2.93 0 0 1-4.126.423l-2.965-2.414a2.933 2.933 0 0 1-.423-4.125z");
}

.zn8-94zmi {
  stop-color: var(--svg-color--1e7249, #1E7249);
  stop-opacity: 0;
}

.znrgouaxn {
  stop-color: var(--svg-color--41c342, #41C342);
}

</style>
