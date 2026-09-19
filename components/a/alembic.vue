<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#i2ZmQjb)" class="y7ff0eblf"/><g filter="url(#i7BGe8b)"><path class="hu0fpub_z"/><path fill="url(#iErDoSa)" class="wn5srusxv"/><path fill="url(#ildGEVc)" class="wn5srusxv"/></g><g filter="url(#irEVc9d)"><path class="d0elssbdt"/></g><g filter="url(#iVmaqLd)"><circle fill="url(#iIeks2c)" class="jpnkoveyo"/></g><circle fill="url(#iAqfPCd)" class="jpnkoveyo"/><path fill="url(#iIsNgqb)" class="lknhbacxh"/><path stroke="url(#iH7yiIV)" class="hrf1-pbdn"/><circle fill="url(#idL8Azb)" class="ywdf0jbsk"/><circle fill="url(#iM77Qzc)" class="pn24-68to"/><circle fill="url(#iCwyatd)" class="g22acobhj"/><path stroke="url(#iG7ql7a)" class="kl4km8zwj"/><g filter="url(#igxdhSg)"><path class="saq_dl18v"/></g><path stroke="url(#iv7jvrc)" class="d8txrzrhl"/><g filter="url(#i3hQKMd)"><path class="h91cbpwws"/></g><path stroke="url(#i77lZ8b)" class="uquv8tbmn"/><path stroke="url(#imo2CNN)" class="uquv8tbmn"/><path stroke="url(#is7Egvb)" class="uquv8tbmn"/><defs><radialGradient id="ildGEVc" cx="0" cy="0" r="1" gradientTransform="matrix(.1598 -.113 .28094 .3973 22.409 11.273)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="xfim81sug"/><stop offset="1" class="h8mrvsbqk"/></radialGradient><radialGradient id="iIeks2c" cx="0" cy="0" r="1" gradientTransform="rotate(157.235 7.835 8.054)scale(9.58066)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="yl10ksbvf"/><stop offset="1" class="rx1rbxb3i"/></radialGradient><radialGradient id="iAqfPCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.72367 15.75 0 13.596 25.661)" gradientUnits="userSpaceOnUse"><stop class="ijfea2ijv"/><stop offset="1" class="a_k57ohpi"/></radialGradient><radialGradient id="iIsNgqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5666 -14.375 0 19.252 15.308)" gradientUnits="userSpaceOnUse"><stop class="mex8km6za"/><stop offset="1" class="mkul-lbla"/></radialGradient><radialGradient id="idL8Azb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .67188 -.58367 -.6651 10.08 16.875)" gradientUnits="userSpaceOnUse"><stop class="pqo1lbcen"/><stop offset="1" class="hexv2u7lo"/></radialGradient><radialGradient id="iM77Qzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .67188 -.58367 -.6651 13.916 17.338)" gradientUnits="userSpaceOnUse"><stop class="pqo1lbcen"/><stop offset="1" class="hexv2u7lo"/></radialGradient><radialGradient id="iCwyatd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .67188 -.58367 -.6651 11.806 22.298)" gradientUnits="userSpaceOnUse"><stop class="tl-i2ablx"/><stop offset="1" class="kpekribuf"/></radialGradient><radialGradient id="is7Egvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .45313 -8.72985 0 18.127 19.852)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="imp2_obhq"/><stop offset="1" class="i_a29vble"/></radialGradient><linearGradient id="i2ZmQjb" x1="14.252" x2="12.721" y1="27.406" y2="27.406" gradientUnits="userSpaceOnUse"><stop class="lc5denbhn"/><stop offset="1" class="ik3lfbnnt"/></linearGradient><linearGradient id="iErDoSa" x1="22.847" x2="23.313" y1="11.703" y2="9.915" gradientUnits="userSpaceOnUse"><stop class="z4mqtj5jw"/><stop offset="1" class="jq0_kn7fo"/></linearGradient><linearGradient id="iH7yiIV" x1="19.222" x2="19.704" y1="11.108" y2="17.3" gradientUnits="userSpaceOnUse"><stop offset=".403" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iG7ql7a" x1="6.346" x2="5.471" y1="25.25" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="rpxic1lsf"/><stop offset="1" class="g1qi-m3cb"/></linearGradient><linearGradient id="iv7jvrc" x1="21.908" x2="20.971" y1="25.438" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="wqr5-ibpv"/><stop offset="1" class="x43jdbcbe"/></linearGradient><linearGradient id="i77lZ8b" x1="11.471" x2="11.533" y1="20.969" y2="19.469" gradientUnits="userSpaceOnUse"><stop class="zgou0_v6t"/><stop offset="1" class="q5k0spcrk"/></linearGradient><linearGradient id="imo2CNN" x1="2.315" x2="6.846" y1="18.906" y2="20.313" gradientUnits="userSpaceOnUse"><stop class="kylmy0b-b"/><stop offset="1" class="z1mx_ab7k"/></linearGradient><filter id="i7BGe8b" width="13.292" height="7.235" x="16.718" y="5.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.788235 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24864"/></filter><filter id="irEVc9d" width="9.61" height="5.281" x="20.252" y="7.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24864" stdDeviation=".25"/></filter><filter id="iVmaqLd" width="21.06" height="21.06" x="2.776" y="4.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.862745 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24864"/></filter><filter id="igxdhSg" width="7.343" height="10.34" x="2.274" y="19.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24864" stdDeviation=".2"/></filter><filter id="i3hQKMd" width="7.343" height="10.34" x="17.234" y="19.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24864" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:alembic" /></template>
<style>
.a_k57ohpi {
  stop-color: var(--svg-color--abc0fc, #ABC0FC);
  stop-opacity: 0;
}

.d0elssbdt {
  fill: var(--svg-color--d7ffff, #D7FFFF);
  d: path("m20.752 7.86l8.61 3.693l-.227.588l-7.921-3.053z");
}

.d8txrzrhl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("m23.836 29.27l-6.142-9.14");
}

.ft5dv1b6b {
  fill: none;
}

.g1qi-m3cb {
  stop-color: var(--svg-color--443163, #443163);
}

.g22acobhj {
  cx: 11.423px;
  cy: 22.478px;
  r: 1.055px;
}

.h8mrvsbqk {
  stop-color: var(--svg-color--dcffff, #DCFFFF);
  stop-opacity: 0;
}

.h91cbpwws {
  stroke: var(--svg-color--6e658c, #6E658C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m23.977 29.127l-6.143-9.14");
}

.hexv2u7lo {
  stop-color: var(--svg-color--b6ee7f, #B6EE7F);
}

.hrf1-pbdn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-25px, 2.25px);
  d: path("M19.222 11.789c.513 1.09 1.364 3.811.75 6.399");
}

.hu0fpub_z {
  fill: var(--svg-color--c5f5ff, #C5F5FF);
  d: path("M29.7 10.674L18.159 5.919l-1.441 3.513l4.84 1.487l.929 1.034l.757-.305c-.021-.068.043-.218.247-.148l5.268 1.632a.5.5 0 0 0 .612-.293l.603-1.519a.5.5 0 0 0-.274-.646");
}

.i_a29vble {
  stop-color: var(--svg-color--716a8e, #716A8E);
  stop-opacity: 0;
}

.ijfea2ijv {
  stop-color: var(--svg-color--abc0fc, #ABC0FC);
}

.ik3lfbnnt {
  stop-color: var(--svg-color--4e3b7d, #4E3B7D);
}

.imp2_obhq {
  stop-color: var(--svg-color--716a8e, #716A8E);
}

.jpnkoveyo {
  cx: 13.306px;
  cy: 15.131px;
  r: 10.53px;
}

.jq0_kn7fo {
  stop-color: var(--svg-color--c7f0ff, #C7F0FF);
  stop-opacity: 0;
}

.kl4km8zwj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("m2.874 29.27l6.143-9.14");
}

.kpekribuf {
  stop-color: var(--svg-color--a8d483, #A8D483);
}

.kylmy0b-b {
  stop-color: var(--svg-color--70677e, #70677E);
}

.lc5denbhn {
  stop-color: var(--svg-color--4f319e, #4F319E);
}

.lknhbacxh {
  d: path("M3.882 15.308a9.426 9.426 0 0 0 18.848 0z");
}

.mex8km6za {
  stop-color: var(--svg-color--4dfa92, #4DFA92);
}

.mkul-lbla {
  stop-color: var(--svg-color--2cb174, #2CB174);
}

.pn24-68to {
  cx: 13.533px;
  cy: 17.518px;
  r: 1.055px;
}

.pqo1lbcen {
  stop-color: var(--svg-color--e4ffba, #E4FFBA);
}

.q5k0spcrk {
  stop-color: var(--svg-color--4f476e, #4F476E);
}

.rpxic1lsf {
  stop-color: var(--svg-color--523082, #523082);
}

.rx1rbxb3i {
  stop-color: var(--svg-color--b6e2ff, #B6E2FF);
}

.saq_dl18v {
  stroke: var(--svg-color--6f5b92, #6F5B92);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m2.874 29.27l6.143-9.14");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tl-i2ablx {
  stop-color: var(--svg-color--caf1a6, #CAF1A6);
}

.uquv8tbmn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.742 19.982h19.266");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wn5srusxv {
  d: path("M29.7 10.674L18.159 5.919l-1.441 3.513l4.84 1.487l.929 1.034l.757-.305c-.021-.068.043-.218.247-.148l5.268 1.632a.5.5 0 0 0 .612-.293l.603-1.519a.5.5 0 0 0-.274-.646");
}

.wqr5-ibpv {
  stop-color: var(--svg-color--3e236e, #3E236E);
}

.x43jdbcbe {
  stop-color: var(--svg-color--39285d, #39285D);
}

.xfim81sug {
  stop-color: var(--svg-color--dcffff, #DCFFFF);
}

.y7ff0eblf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M13.533 29.27v-5.6");
}

.yl10ksbvf {
  stop-color: var(--svg-color--d8ffff, #D8FFFF);
}

.ywdf0jbsk {
  cx: 9.697px;
  cy: 17.055px;
  r: 1.055px;
}

.z1mx_ab7k {
  stop-color: var(--svg-color--70677e, #70677E);
  stop-opacity: 0;
}

.z4mqtj5jw {
  stop-color: var(--svg-color--add0ff, #ADD0FF);
}

.zgou0_v6t {
  stop-color: var(--svg-color--481a77, #481A77);
}

</style>
