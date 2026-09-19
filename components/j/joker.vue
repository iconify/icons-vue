<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifASGUd)"><rect fill="url(#in9x4jb)" class="gemg08bzj"/></g><rect fill="url(#i9vlAlx)" class="gemg08bzj"/><rect fill="url(#itJ64Be)" class="gemg08bzj"/><rect fill="url(#iwrelGY)" class="gemg08bzj"/><rect fill="url(#icIC7LE)" class="gemg08bzj"/><g filter="url(#irPzOxO)"><path fill="url(#iaJ1Fzc)" class="m4e59vj3g"/></g><rect fill="url(#iPYeJNd)" class="togmrdb3u"/><g filter="url(#iDDljRq)"><path fill="url(#il3UKqc)" class="nsjaggbuz"/></g><g filter="url(#i3OryBA)"><path fill="url(#izANuVk)" class="e3o6gvu4e"/></g><path fill="url(#i4fPTce)" class="pa6vo24ue"/><path fill="url(#iHxDghb)" class="nxmucuqab"/><path fill="url(#iAZsYad)" class="nxmucuqab"/><g filter="url(#iQusY5a)"><circle fill="url(#i4ASgrb)" class="y3apkx9lw"/></g><path fill="url(#iRLiLFc)" class="ui9729inq"/><path fill="url(#idoLSgb)" class="ui9729inq"/><g filter="url(#iNPyvze)"><circle fill="url(#izApNXd)" class="e7hxoh_tp"/></g><g filter="url(#iEFKvje)"><circle fill="url(#ih7z3Xo)" class="gjk5jrbyg"/></g><defs><linearGradient id="in9x4jb" x1="16.062" x2="16.062" y1="2.134" y2="30.134" gradientUnits="userSpaceOnUse"><stop class="biy93mebn"/><stop offset="1" class="x1bve1g2n"/></linearGradient><linearGradient id="i9vlAlx" x1="16.062" x2="16.062" y1="1.884" y2="3.197" gradientUnits="userSpaceOnUse"><stop class="sms71ibmt"/><stop offset="1" class="os37q3hum"/></linearGradient><linearGradient id="iwrelGY" x1="16.062" x2="16.062" y1="31.545" y2="28.117" gradientUnits="userSpaceOnUse"><stop class="sh2ofp9wk"/><stop offset="1" class="t4enrnb6s"/></linearGradient><linearGradient id="icIC7LE" x1="16.062" x2="16.062" y1="30.197" y2="29.767" gradientUnits="userSpaceOnUse"><stop class="fk6vgjs6j"/><stop offset="1" class="tu7przbjf"/></linearGradient><linearGradient id="iaJ1Fzc" x1="19.757" x2="11.101" y1="19.353" y2="19.353" gradientUnits="userSpaceOnUse"><stop class="ccj723bgl"/><stop offset="1" class="yj8qla6tn"/></linearGradient><linearGradient id="il3UKqc" x1="19.773" x2="19.773" y1="11.306" y2="16.572" gradientUnits="userSpaceOnUse"><stop class="sjdok29pb"/><stop offset=".757" class="wr28ptbyo"/></linearGradient><linearGradient id="izANuVk" x1="12.093" x2="12.093" y1="11.306" y2="16.572" gradientUnits="userSpaceOnUse"><stop class="p0bh_4kdv"/><stop offset=".757" class="jks7zykus"/></linearGradient><linearGradient id="i4fPTce" x1="17.507" x2="14.976" y1="19.353" y2="19.884" gradientUnits="userSpaceOnUse"><stop class="n0aj-pb6b"/><stop offset="1" class="zll07hy5k"/></linearGradient><linearGradient id="iHxDghb" x1="16.03" x2="16.03" y1="7.853" y2="15.759" gradientUnits="userSpaceOnUse"><stop class="qidbj8bsw"/><stop offset="1" class="z_ckpdbid"/></linearGradient><linearGradient id="iAZsYad" x1="17.07" x2="16.616" y1="9.697" y2="9.838" gradientUnits="userSpaceOnUse"><stop class="g50ryqbvn"/><stop offset="1" class="n9v-adqei"/></linearGradient><linearGradient id="iRLiLFc" x1="13.038" x2="19.663" y1="16.166" y2="16.166" gradientUnits="userSpaceOnUse"><stop class="tc4_fgb3p"/><stop offset="1" class="irqt_nb0z"/></linearGradient><linearGradient id="idoLSgb" x1="12.398" x2="13.007" y1="16.759" y2="16.759" gradientUnits="userSpaceOnUse"><stop class="mezkygbsy"/><stop offset="1" class="vchdu4b0d"/></linearGradient><filter id="ifASGUd" width="24" height="30" x="4.062" y="1.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.721569 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.913725 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4077" result="effect2_innerShadow_18_4077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.803922 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_4077" result="effect3_innerShadow_18_4077"/></filter><filter id="irPzOxO" width="11.624" height="6.629" x="10.336" y="18.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.368627 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.529412 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4077" result="effect2_innerShadow_18_4077"/></filter><filter id="iDDljRq" width="6.381" height="5.366" x="16.532" y="11.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.760784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/></filter><filter id="i3OryBA" width="5.725" height="5.366" x="9.181" y="11.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.392157 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/></filter><filter id="iQusY5a" width="2.741" height="2.741" x="14.649" y="6.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.933333 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/></filter><filter id="iNPyvze" width="2.641" height="2.741" x="21.718" y="12.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.917647 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/></filter><filter id="iEFKvje" width="2.641" height="2.741" x="7.765" y="12.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.34902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4077"/></filter><radialGradient id="itJ64Be" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 1.26563 -.71254 -.8093 26.929 2.416)" gradientUnits="userSpaceOnUse"><stop class="z3k-hfn7o"/><stop offset="1" class="z7gp53b4s"/></radialGradient><radialGradient id="iPYeJNd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.12497 4.50003 -3.50575 -3.21356 18.882 16.353)" gradientUnits="userSpaceOnUse"><stop class="krp9yoowm"/><stop offset="1" class="vxokpxbzj"/></radialGradient><radialGradient id="i4ASgrb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 1.9375 -2.4941 -2.1723 16.913 7.04)" gradientUnits="userSpaceOnUse"><stop class="rb-1x-b1t"/><stop offset="1" class="p2faax1oe"/></radialGradient><radialGradient id="izApNXd" cx="0" cy="0" r="1" gradientTransform="scale(3.33888 2.59375)rotate(90 .945 6.02)" gradientUnits="userSpaceOnUse"><stop class="dvrijcbbb"/><stop offset="1" class="dipsk5bby"/></radialGradient><radialGradient id="ih7z3Xo" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64062 0 0 -3.39922 10.405 13.978)" gradientUnits="userSpaceOnUse"><stop class="zdckpb0zq"/><stop offset="1" class="zjkluhc4c"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:joker" /></template>
<style>
.biy93mebn {
  stop-color: var(--svg-color--d8d4dd, #D8D4DD);
}

.ccj723bgl {
  stop-color: var(--svg-color--9072cb, #9072CB);
}

.dipsk5bby {
  stop-color: var(--svg-color--3dabf4, #3DABF4);
}

.dvrijcbbb {
  stop-color: var(--svg-color--5fd9ff, #5FD9FF);
}

.e3o6gvu4e {
  d: path("M12.75 11.306c1.187.025 1.932.771 2.156 1.14v3.22l-2.547.906v-2.218a.9.9 0 0 0-1.402-.747l-.692.465l-.984-.656l1.124-1.188c.287-.318 1.157-.947 2.344-.922");
}

.e7hxoh_tp {
  cx: 23.038px;
  cy: 14.283px;
  r: 1.32px;
}

.fk6vgjs6j {
  stop-color: var(--svg-color--b094ca, #B094CA);
}

.ft5dv1b6b {
  fill: none;
}

.g50ryqbvn {
  stop-color: var(--svg-color--f9e85c, #F9E85C);
}

.gemg08bzj {
  width: 22px;
  height: 28px;
  x: 5.062px;
  y: 2.134px;
  rx: 1.5px;
}

.gjk5jrbyg {
  cx: 9.085px;
  cy: 14.283px;
  r: 1.32px;
}

.irqt_nb0z {
  stop-color: var(--svg-color--756ba4, #756BA4);
}

.jks7zykus {
  stop-color: var(--svg-color--eb4755, #EB4755);
}

.krp9yoowm {
  stop-color: var(--svg-color--f1b1a4, #F1B1A4);
}

.m4e59vj3g {
  d: path("m12.929 18.134l-2.273 2.284a.75.75 0 0 0 .531 1.279h2.117v2.115c0 .663.797 1 1.273.538l1.57-1.528l1.572 1.528a.75.75 0 0 0 1.272-.538v-2.115h2.117a.75.75 0 0 0 .532-1.28l-2.274-2.283z");
}

.mezkygbsy {
  stop-color: var(--svg-color--8f6bcc, #8F6BCC);
}

.n0aj-pb6b {
  stop-color: var(--svg-color--eb4488, #EB4488);
}

.n9v-adqei {
  stop-color: var(--svg-color--f9e85c, #F9E85C);
  stop-opacity: 0;
}

.nsjaggbuz {
  d: path("M19.445 11.306c-1.188.025-1.933.771-2.157 1.14l-.656 2.938l3.203 1.188v-2.218a.9.9 0 0 1 1.402-.747l.692.465l.984-.656l-1.125-1.188c-.286-.318-1.156-.947-2.343-.922");
}

.nxmucuqab {
  d: path("m13.554 15.76l2.188-7.907h.718l2.047 7.906z");
}

.os37q3hum {
  stop-color: var(--svg-color--d6d5d7, #D6D5D7);
  stop-opacity: 0;
}

.p0bh_4kdv {
  stop-color: var(--svg-color--ea448b, #EA448B);
}

.p2faax1oe {
  stop-color: var(--svg-color--f1be42, #F1BE42);
}

.pa6vo24ue {
  d: path("M14.695 18.955a1.406 1.406 0 0 0 2.812 0z");
}

.qidbj8bsw {
  stop-color: var(--svg-color--f4df4a, #F4DF4A);
}

.rb-1x-b1t {
  stop-color: var(--svg-color--f4e04b, #F4E04B);
}

.sh2ofp9wk {
  stop-color: var(--svg-color--b9a5ce, #B9A5CE);
}

.sjdok29pb {
  stop-color: var(--svg-color--44b0f4, #44B0F4);
}

.sms71ibmt {
  stop-color: var(--svg-color--d6d5d7, #D6D5D7);
}

.t4enrnb6s {
  stop-color: var(--svg-color--b9a5ce, #B9A5CE);
  stop-opacity: 0;
}

.tc4_fgb3p {
  stop-color: var(--svg-color--8f71c8, #8F71C8);
}

.togmrdb3u {
  width: 7.438px;
  height: 9.547px;
  x: 12.398px;
  y: 11.947px;
  rx: 3.719px;
}

.tu7przbjf {
  stop-color: var(--svg-color--b094ca, #B094CA);
  stop-opacity: 0;
}

.ui9729inq {
  d: path("M12.398 17.397v-1.69a5.8 5.8 0 0 1 3.633-1.276c1.455 0 2.785.535 3.804 1.42v1.718c-.981-1.023-2.324-1.653-3.805-1.653c-1.395 0-2.669.56-3.632 1.481");
}

.vchdu4b0d {
  stop-color: var(--svg-color--8f6acc, #8F6ACC);
  stop-opacity: 0;
}

.vxokpxbzj {
  stop-color: var(--svg-color--e9978f, #E9978F);
}

.wr28ptbyo {
  stop-color: var(--svg-color--5dd7ff, #5DD7FF);
}

.x1bve1g2n {
  stop-color: var(--svg-color--dbd5e3, #DBD5E3);
}

.y3apkx9lw {
  cx: 16.07px;
  cy: 7.939px;
  r: 1.32px;
}

.yj8qla6tn {
  stop-color: var(--svg-color--796baa, #796BAA);
}

.z_ckpdbid {
  stop-color: var(--svg-color--f3cd4a, #F3CD4A);
}

.z3k-hfn7o {
  stop-color: var(--svg-color--f5f4f7, #F5F4F7);
}

.z7gp53b4s {
  stop-color: var(--svg-color--f5f4f7, #F5F4F7);
  stop-opacity: 0;
}

.zdckpb0zq {
  stop-color: var(--svg-color--eb488e, #EB488E);
}

.zjkluhc4c {
  stop-color: var(--svg-color--eb465e, #EB465E);
}

.zll07hy5k {
  stop-color: var(--svg-color--ec4953, #EC4953);
}

</style>
