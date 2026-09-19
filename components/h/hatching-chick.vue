<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4kwxoX)" class="v87y2kbcq"/><path fill="url(#i0fxilc)" class="v87y2kbcq"/><path fill="url(#iAMQ6Ib)" class="i87t0yxfa"/><path fill="url(#iELXbvb)" class="i87t0yxfa"/><path fill="url(#ikFAD8I)" class="i87t0yxfa"/><path fill="url(#iFznizb)" class="i87t0yxfa"/><path fill="url(#iha0VQb)" class="avk34ey6b"/><path fill="url(#iPVreyb)" class="avk34ey6b"/><path fill="url(#ia9gUYb)" class="avk34ey6b"/><path fill="url(#iVwfscd)" class="avk34ey6b"/><path fill="url(#ikJkHuN)" class="avk34ey6b"/><path fill="url(#iyaQl2Y)" class="avk34ey6b"/><path fill="url(#ioNXpKk)" class="avk34ey6b"/><g filter="url(#iJRxREa)"><ellipse fill="url(#iLp90Ab)" transform="rotate(28.818 17.806 7.073)" class="kv7nl_b9p"/></g><g filter="url(#iQTW7dc)"><path fill="url(#i4iUL0d)" class="l6pmkabmq"/><path fill="url(#i4LaQpe)" class="l6pmkabmq"/><path fill="url(#iNLJZMe)" class="l6pmkabmq"/><path fill="url(#iMUXssb)" class="l6pmkabmq"/><path fill="url(#i7ExgDP)" class="l6pmkabmq"/><path fill="url(#ixALhhD)" class="l6pmkabmq"/></g><g filter="url(#iY1m0Ob)"><ellipse fill="url(#ick3JPE)" transform="rotate(-16.631 15.198 9.688)" class="y8n03dbef"/></g><path fill="url(#ibl9Dvb)" class="ksqyhtb9x"/><path fill="url(#iBTkwde)" class="ksqyhtb9x"/><path fill="url(#ionuB8c)" class="ksqyhtb9x"/><path fill="url(#iK8Laod)" class="c_pb3-ble"/><path fill="url(#id45VEe)" class="c_pb3-ble"/><path fill="url(#iSmD5Ob)" class="c_pb3-ble"/><path class="dypurbcze"/><path fill="url(#iTHIzEe)" class="vgvkafbas"/><path fill="url(#iYocK5d)" class="vgvkafbas"/><path fill="url(#iKS8mRb)" class="vgvkafbas"/><g filter="url(#iLWfcOb)"><ellipse fill="url(#iZS2B1Y)" transform="rotate(-34.23 9.279 22.474)" class="op036cc_u"/></g><defs><radialGradient id="i4kwxoX" cx="0" cy="0" r="1" gradientTransform="matrix(10.1019 4.96072 -2.80272 5.70739 1.518 10.05)" gradientUnits="userSpaceOnUse"><stop class="is9qfpv-a"/><stop offset="1" class="kdsgmdb2f"/><stop offset="1" class="xu3n57brn"/></radialGradient><radialGradient id="iELXbvb" cx="0" cy="0" r="1" gradientTransform="rotate(156.138 17.221 7.825)scale(12.5688 1.52199)" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset="1" class="ylm81nbmc"/></radialGradient><radialGradient id="ikFAD8I" cx="0" cy="0" r="1" gradientTransform="rotate(154.22 13.808 8.731)scale(1.91466 1.09139)" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset=".513" class="ylm81nbmc"/></radialGradient><radialGradient id="iPVreyb" cx="0" cy="0" r="1" gradientTransform="matrix(-18.94587 -17.41796 13.75688 -14.96364 24.389 20.726)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="c9l33wawe"/><stop offset="1" class="yrvcnfy6o"/></radialGradient><radialGradient id="iVwfscd" cx="0" cy="0" r="1" gradientTransform="matrix(10.6326 -8.4083 8.33864 10.5445 9.845 17.25)" gradientUnits="userSpaceOnUse"><stop class="xuqllht4b"/><stop offset="1" class="bivxxmbgy"/></radialGradient><radialGradient id="ikJkHuN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.875 2.48438 0 21.658 18.75)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="btbm5bbop"/><stop offset="1" class="iieazgb6v"/></radialGradient><radialGradient id="iyaQl2Y" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.1875 2.68473 0 10.158 18.875)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="btbm5bbop"/><stop offset="1" class="iieazgb6v"/></radialGradient><radialGradient id="ioNXpKk" cx="0" cy="0" r="1" gradientTransform="rotate(-130.956 10.622 6.027)scale(4.38615 5.89747)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="btbm5bbop"/><stop offset="1" class="iieazgb6v"/></radialGradient><radialGradient id="i4LaQpe" cx="0" cy="0" r="1" gradientTransform="rotate(137.555 4.966 11.71)scale(16.8547 16.6376)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="gf0nkrb9s"/><stop offset="1" class="pmtupr-9k"/></radialGradient><radialGradient id="iNLJZMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 1.6875 -11.27871 10.0255 3.44 16.125)" gradientUnits="userSpaceOnUse"><stop class="pmtupr-9k"/><stop offset=".686" class="gf0nkrb9s"/></radialGradient><radialGradient id="iMUXssb" cx="0" cy="0" r="1" gradientTransform="matrix(1.12503 10.43754 -8.91684 .96112 23.158 15.656)" gradientUnits="userSpaceOnUse"><stop class="i56kxacrh"/><stop offset="1" class="dmmn2gkqv"/></radialGradient><radialGradient id="i7ExgDP" cx="0" cy="0" r="1" gradientTransform="matrix(16.87498 6.24998 -7.3916 19.95736 13.97 16.563)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="gf0nkrb9s"/><stop offset=".949" class="pmtupr-9k"/></radialGradient><radialGradient id="ixALhhD" cx="0" cy="0" r="1" gradientTransform="rotate(-125.828 21.878 11.519)scale(18.365 17.1085)" gradientUnits="userSpaceOnUse"><stop class="fshhkigay"/><stop offset=".931" class="iaq69jp0q"/></radialGradient><radialGradient id="ibl9Dvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 11.595 7.343)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iBTkwde" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 4.387 5.943)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iK8Laod" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 20.69 7.343)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="id45VEe" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 8.935 7.705)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iTHIzEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 1.6875 0 16.861 8.937)" gradientUnits="userSpaceOnUse"><stop class="nelj53t4g"/><stop offset="1" class="z0s76ztds"/></radialGradient><radialGradient id="iKS8mRb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -1.46375 .31043 .05302 14.58 9.594)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="nelj53t4g"/><stop offset="1" class="z0s76ztds"/></radialGradient><radialGradient id="iZS2B1Y" cx="0" cy="0" r="1" gradientTransform="matrix(9.15845 -.23934 .5445 20.83529 6.079 20.298)" gradientUnits="userSpaceOnUse"><stop class="yub77bc9u"/><stop offset=".62" class="z2vsfv0ny"/></radialGradient><linearGradient id="i0fxilc" x1="8.814" x2="6.641" y1="15.906" y2="16.151" gradientUnits="userSpaceOnUse"><stop class="jtg6tpb4j"/><stop offset="1" class="i99n8gbfa"/></linearGradient><linearGradient id="iAMQ6Ib" x1="30.582" x2="24.02" y1="8.554" y2="16.111" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="iFznizb" x1="27.288" x2="26.483" y1="15.461" y2="13.489" gradientUnits="userSpaceOnUse"><stop class="goz4r_b1j"/><stop offset="1" class="oqnfxh0ll"/></linearGradient><linearGradient id="iha0VQb" x1="15.996" x2="15.996" y1=".031" y2="22.245" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="ia9gUYb" x1="9.489" x2="7.092" y1="13.522" y2="13.522" gradientUnits="userSpaceOnUse"><stop class="c9l33wawe"/><stop offset="1" class="yrvcnfy6o"/></linearGradient><linearGradient id="iLp90Ab" x1="18.028" x2="17.806" y1="1.624" y2="10.641" gradientUnits="userSpaceOnUse"><stop class="h_yie6boz"/><stop offset="1" class="qvgke0beh"/></linearGradient><linearGradient id="i4iUL0d" x1="15.996" x2="15.996" y1="12.813" y2="32.813" gradientUnits="userSpaceOnUse"><stop class="a4i8gfb5z"/><stop offset="1" class="dhylvwb6s"/></linearGradient><linearGradient id="ick3JPE" x1="17.365" x2="10.58" y1="9.799" y2="10.861" gradientUnits="userSpaceOnUse"><stop class="dunrcrk5s"/><stop offset="1" class="et-gawdcu"/></linearGradient><linearGradient id="ionuB8c" x1="11.349" x2="11.005" y1="7.111" y2="6.893" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iSmD5Ob" x1="20.445" x2="20.101" y1="7.111" y2="6.893" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iYocK5d" x1="15.995" x2="15.995" y1="9.172" y2="8.75" gradientUnits="userSpaceOnUse"><stop class="pxfj-dbvr"/><stop offset=".787" class="oxil90f4i"/></linearGradient><filter id="iJRxREa" width="13.742" height="11.392" x="10.935" y="1.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4754" stdDeviation=".75"/></filter><filter id="iQTW7dc" width="25.616" height="18.617" x="3.232" y="11.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.615686 0 0 0 0 0.6 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4754"/></filter><filter id="iY1m0Ob" width="7.08" height="4.394" x="11.658" y="7.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4754" stdDeviation=".5"/></filter><filter id="iLWfcOb" width="11.286" height="13.114" x="3.635" y="15.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4754" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hatching-chick" /></template>
<style>
.a4i8gfb5z {
  stop-color: var(--svg-color--ded6e7, #DED6E7);
}

.avk34ey6b {
  d: path("M16 2c-4.44 0-8.03 3.59-8.03 8.03v9.26h16.06v-9.26C24.02 5.59 20.43 2 16 2");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bivxxmbgy {
  stop-color: var(--svg-color--d18b2b, #D18B2B);
  stop-opacity: 0;
}

.btbm5bbop {
  stop-color: var(--svg-color--d6722e, #D6722E);
}

.c_pb3-ble {
  d: path("M20.543 8.004a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.c9l33wawe {
  stop-color: var(--svg-color--bba553, #BBA553);
  stop-opacity: 0;
}

.dhylvwb6s {
  stop-color: var(--svg-color--c0aadd, #C0AADD);
}

.dmmn2gkqv {
  stop-color: var(--svg-color--ebe3f2, #EBE3F2);
  stop-opacity: 0;
}

.dunrcrk5s {
  stop-color: var(--svg-color--e5951b, #E5951B);
}

.dypurbcze {
  fill: var(--svg-color--ed6c32, #ED6C32);
  d: path("M17.92 9.09h-3.85c0-1.06.86-1.92 1.92-1.92s1.93.86 1.93 1.92");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.et-gawdcu {
  stop-color: var(--svg-color--e5951b, #E5951B);
  stop-opacity: 0;
}

.fshhkigay {
  stop-color: var(--svg-color--a58bc3, #A58BC3);
}

.ft5dv1b6b {
  fill: none;
}

.gf0nkrb9s {
  stop-color: var(--svg-color--aea7bb, #AEA7BB);
  stop-opacity: 0;
}

.goz4r_b1j {
  stop-color: var(--svg-color--d39344, #D39344);
}

.h_yie6boz {
  stop-color: var(--svg-color--f8e31d, #F8E31D);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i56kxacrh {
  stop-color: var(--svg-color--ebe3f2, #EBE3F2);
}

.i87t0yxfa {
  d: path("m24.02 17.85l5.65-5.65c.79-.79.23-2.15-.89-2.15h-4.76z");
}

.i99n8gbfa {
  stop-color: var(--svg-color--cd7c10, #CD7C10);
  stop-opacity: 0;
}

.iaq69jp0q {
  stop-color: var(--svg-color--a58bc3, #A58BC3);
  stop-opacity: 0;
}

.iieazgb6v {
  stop-color: var(--svg-color--d6722e, #D6722E);
  stop-opacity: 0;
}

.is9qfpv-a {
  stop-color: var(--svg-color--dab830, #DAB830);
}

.jtg6tpb4j {
  stop-color: var(--svg-color--cd7c10, #CD7C10);
}

.kdsgmdb2f {
  stop-color: var(--svg-color--b96d1e, #B96D1E);
}

.ksqyhtb9x {
  d: path("M11.447 8.004a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.kv7nl_b9p {
  cx: 17.806px;
  cy: 7.073px;
  rx: 5.806px;
  ry: 3.568px;
}

.l6pmkabmq {
  d: path("M25.427 14.318a.25.25 0 0 0-.355 0l-3.105 3.105a.25.25 0 0 1-.354 0l-5.446-5.446a.25.25 0 0 0-.354 0l-5.446 5.446a.25.25 0 0 1-.354 0l-3.096-3.096a.25.25 0 0 0-.354 0l-3.187 3.187a.5.5 0 0 0-.144.354c.11 6.954 5.777 12.552 12.758 12.552c6.97 0 12.638-5.598 12.758-12.543a.5.5 0 0 0-.143-.353z");
}

.lr_grnbee {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
}

.nelj53t4g {
  stop-color: var(--svg-color--ff8e64, #FF8E64);
}

.op036cc_u {
  cx: 9.279px;
  cy: 22.474px;
  rx: 3.679px;
  ry: 6.236px;
}

.oqnfxh0ll {
  stop-color: var(--svg-color--df9d4c, #DF9D4C);
  stop-opacity: 0;
}

.oxil90f4i {
  stop-color: var(--svg-color--ea6038, #EA6038);
  stop-opacity: 0;
}

.pmtupr-9k {
  stop-color: var(--svg-color--87838e, #87838E);
}

.pxfj-dbvr {
  stop-color: var(--svg-color--c1411b, #C1411B);
}

.qvgke0beh {
  stop-color: var(--svg-color--f8e31d, #F8E31D);
  stop-opacity: 0;
}

.v87y2kbcq {
  d: path("M7.99 17.85L2.34 12.2c-.79-.79-.23-2.15.89-2.15h4.76z");
}

.vgvkafbas {
  d: path("M17.92 9.09h-3.85c0-1.06.86-1.92 1.92-1.92s1.93.86 1.93 1.92");
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.xu3n57brn {
  stop-color: var(--svg-color--db8021, #DB8021);
}

.xuqllht4b {
  stop-color: var(--svg-color--bd7614, #BD7614);
}

.y8n03dbef {
  cx: 15.198px;
  cy: 9.688px;
  rx: 2.635px;
  ry: 0.97px;
}

.ylm81nbmc {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
  stop-opacity: 0;
}

.yrvcnfy6o {
  stop-color: var(--svg-color--bba553, #BBA553);
}

.yub77bc9u {
  stop-color: var(--svg-color--e7ddf9, #E7DDF9);
}

.z0s76ztds {
  stop-color: var(--svg-color--ff8e64, #FF8E64);
  stop-opacity: 0;
}

.z2vsfv0ny {
  stop-color: var(--svg-color--e7ddf9, #E7DDF9);
  stop-opacity: 0;
}

</style>
