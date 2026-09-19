<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1W5Yrb)"><path class="pa-0iub3e"/><path fill="url(#iT1gjYc)" class="w7zguz1oo"/><path fill="url(#i8xWosd)" class="w7zguz1oo"/></g><g filter="url(#iKPDVde)"><rect class="hyv1xnbif"/></g><g filter="url(#iCixzPD)"><rect class="e1u2adbkw"/></g><path class="sautvobyf"/><path fill="url(#iJeF9ir)" class="w14p2xbrq"/><path fill="url(#iW3212b)" class="w14p2xbrq"/><path fill="url(#iiAJYGb)" class="w14p2xbrq"/><path fill="url(#i4WcKPb)" class="w14p2xbrq"/><path fill="url(#iibljwc)" class="on-jig2mf"/><path fill="url(#ixC16vV)" class="on-jig2mf"/><path fill="url(#iVG0Fib)" class="on-jig2mf"/><path fill="url(#iwamvHb)" class="on-jig2mf"/><g filter="url(#iir9wCc)"><rect fill="url(#ig6bD9b)" class="av4zqtatd"/><rect fill="url(#iGoSOOb)" class="av4zqtatd"/><rect fill="url(#iK4qiNc)" class="av4zqtatd"/></g><g filter="url(#isyc0Eb)"><rect fill="url(#iPl0Wsb)" class="c0i7ullvj"/></g><g filter="url(#iu1TPhP)"><rect fill="url(#i3xPxkd)" class="alyqxwb2b"/></g><g filter="url(#iEWQoOc)"><rect class="df7eoy9jx"/></g><defs><radialGradient id="iT1gjYc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.16814 1.9123 -1.03264 -3.33077 9.852 11.988)" gradientUnits="userSpaceOnUse"><stop class="i-3f06b8s"/><stop offset="1" class="t5_l5rb5e"/></radialGradient><radialGradient id="i8xWosd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.93158 3.02526 -4.1051 -12.11964 23.622 18.334)" gradientUnits="userSpaceOnUse"><stop class="vs49h202c"/><stop offset="1" class="llto44j0y"/></radialGradient><radialGradient id="iJeF9ir" cx="0" cy="0" r="1" gradientTransform="rotate(170.185 14.465 10.245)scale(8.18707 12.8551)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="j-2jj1afw"/><stop offset="1" class="omhb69gtv"/></radialGradient><radialGradient id="iW3212b" cx="0" cy="0" r="1" gradientTransform="rotate(135.167 9.307 15.388)scale(8.73491 1.93512)" gradientUnits="userSpaceOnUse"><stop class="d8_jkpoas"/><stop offset="1" class="vs98v1bqj"/></radialGradient><radialGradient id="iiAJYGb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73778 1.4406 -1.64432 -3.12494 29.601 13.76)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="i7q65hbym"/><stop offset="1" class="l0_fn5b0x"/></radialGradient><radialGradient id="i4WcKPb" cx="0" cy="0" r="1" gradientTransform="rotate(59.5 .502 28.11)scale(.86367 2.71772)" gradientUnits="userSpaceOnUse"><stop class="n9pcic_uc"/><stop offset="1" class="g7m2wwb3m"/></radialGradient><radialGradient id="iVG0Fib" cx="0" cy="0" r="1" gradientTransform="matrix(-2.55702 2.9414 -4.98997 -4.33786 22.83 2.067)" gradientUnits="userSpaceOnUse"><stop class="jl-1u5bfr"/><stop offset="1" class="td79j7bjm"/></radialGradient><radialGradient id="iwamvHb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 0 0 3.0625 17.463 9.919)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="ncyi1tt0s"/><stop offset="1" class="lky6qqhnu"/></radialGradient><radialGradient id="iK4qiNc" cx="0" cy="0" r="1" gradientTransform="rotate(149.179 5.226 7.013)scale(1.07751 2.24971)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="u0230sz1k"/><stop offset="1" class="cp7yf0bpk"/></radialGradient><filter id="i1W5Yrb" width="26.567" height="28.515" x="3.684" y="1.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.486275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2320"/></filter><filter id="iKPDVde" width="6.696" height="8.966" x="10.804" y="10.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2320" stdDeviation=".75"/></filter><filter id="iCixzPD" width="8.409" height="11.255" x="5.696" y="8.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2320" stdDeviation="1"/></filter><filter id="iir9wCc" width="5.922" height="8.922" x="8.135" y="8.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.533333 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2320"/></filter><filter id="isyc0Eb" width="5.828" height="10.484" x="12.698" y="6.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.533333 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2320"/></filter><filter id="iu1TPhP" width="4.636" height="13.444" x="18.332" y="2.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2320" stdDeviation=".75"/></filter><filter id="iEWQoOc" width="5.468" height="10.264" x="13.519" y="7.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2320" stdDeviation="1"/></filter><linearGradient id="iibljwc" x1="16.874" x2="18.797" y1="8.394" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="oenkegbgm"/><stop offset="1" class="xzcr82v6m"/></linearGradient><linearGradient id="ixC16vV" x1="19.337" x2="19.337" y1="12.788" y2="10.411" gradientUnits="userSpaceOnUse"><stop class="hnq-rhrts"/><stop offset="1" class="b7p564b8w"/></linearGradient><linearGradient id="ig6bD9b" x1="9.454" x2="12.282" y1="11.542" y2="11.655" gradientUnits="userSpaceOnUse"><stop class="p-6zavbqs"/><stop offset="1" class="rxiiszonf"/></linearGradient><linearGradient id="iGoSOOb" x1="12.918" x2="12.408" y1="13.005" y2="13.005" gradientUnits="userSpaceOnUse"><stop class="i72060buz"/><stop offset="1" class="da4i23b7s"/></linearGradient><linearGradient id="iPl0Wsb" x1="13.55" x2="17.776" y1="10.616" y2="10.616" gradientUnits="userSpaceOnUse"><stop class="p-6zavbqs"/><stop offset="1" class="rxiiszonf"/></linearGradient><linearGradient id="i3xPxkd" x1="20.65" x2="20.65" y1="3.697" y2="14.141" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:love-you-gesture" /></template>
<style>
.alyqxwb2b {
  width: 1.636px;
  height: 10.444px;
  x: 19.832px;
  y: 3.697px;
  rx: 0.818px;
}

.av4zqtatd {
  width: 5.172px;
  height: 8.172px;
  x: 8.135px;
  y: 8.919px;
  rx: 2.539px;
}

.b7p564b8w {
  stop-color: var(--svg-color--fec942, #FEC942);
  stop-opacity: 0;
}

.c0i7ullvj {
  width: 5.078px;
  height: 9.734px;
  x: 12.698px;
  y: 7.356px;
  rx: 2.539px;
}

.cp7yf0bpk {
  stop-color: var(--svg-color--ad690c, #AD690C);
  stop-opacity: 0;
}

.d8_jkpoas {
  stop-color: var(--svg-color--f2a159, #F2A159);
}

.da4i23b7s {
  stop-color: var(--svg-color--e59617, #E59617);
  stop-opacity: 0;
}

.df7eoy9jx {
  width: 1.468px;
  height: 6.264px;
  x: 15.519px;
  y: 9.092px;
  fill: var(--svg-color--ffe948, #FFE948);
  rx: 0.734px;
}

.e1u2adbkw {
  width: 4.409px;
  height: 7.256px;
  x: 7.696px;
  y: 10.234px;
  fill: var(--svg-color--b44b10, #B44B10);
  rx: 2.204px;
}

.fgz6lbb_q {
  stop-color: var(--svg-color--ffe948, #FFE948);
}

.ft5dv1b6b {
  fill: none;
}

.g7m2wwb3m {
  stop-color: var(--svg-color--d4a33c, #D4A33C);
  stop-opacity: 0;
}

.hnq-rhrts {
  stop-color: var(--svg-color--fec942, #FEC942);
}

.hyv1xnbif {
  width: 3.696px;
  height: 5.966px;
  x: 12.304px;
  y: 11.524px;
  fill: var(--svg-color--b44b10, #B44B10);
  rx: 1.848px;
}

.i-3f06b8s {
  stop-color: var(--svg-color--e79330, #E79330);
}

.i72060buz {
  stop-color: var(--svg-color--e59617, #E59617);
}

.i7q65hbym {
  stop-color: var(--svg-color--ffe847, #FFE847);
}

.j-2jj1afw {
  stop-color: var(--svg-color--ffdc42, #FFDC42);
  stop-opacity: 0;
}

.jl-1u5bfr {
  stop-color: var(--svg-color--ffe645, #FFE645);
}

.l0_fn5b0x {
  stop-color: var(--svg-color--ffe847, #FFE847);
  stop-opacity: 0;
}

.lky6qqhnu {
  stop-color: var(--svg-color--d17703, #D17703);
  stop-opacity: 0;
}

.llto44j0y {
  stop-color: var(--svg-color--ffe542, #FFE542);
  stop-opacity: 0;
}

.n9pcic_uc {
  stop-color: var(--svg-color--d4a33c, #D4A33C);
}

.ncyi1tt0s {
  stop-color: var(--svg-color--d17703, #D17703);
}

.oenkegbgm {
  stop-color: var(--svg-color--e3961f, #E3961F);
}

.omhb69gtv {
  stop-color: var(--svg-color--ffdc42, #FFDC42);
}

.on-jig2mf {
  d: path("M22.476 12.54h-5.288l.038-7.504c0-1.844 1.219-2.969 2.625-2.969c1.5 0 2.625 1.297 2.625 2.97z");
}

.p-6zavbqs {
  stop-color: var(--svg-color--fabb25, #FABB25);
}

.pa-0iub3e {
  fill: var(--svg-color--ffbf40, #FFBF40);
  d: path("M28.995 13.606c-.699-.808-2.063-1.289-3.297-.648c-1.235.64-2.208 1.376-2.578 1.723c0 0-.649.444-.649-.385v-9.26c0-1.672-1.125-2.969-2.625-2.969c-1.406 0-2.625 1.125-2.625 2.97l-.038 7.506H8.909V8.567c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.103 4.328 10.26 9.653 10.26c2.709 0 5.41-1.22 7.189-3.092c2.258-2.375 1.563-3.313 3.961-5.867c1.21-1.383 3.139-2.707 4.195-3.579c1.057-.87 1.258-2.695.313-3.789");
}

.rxiiszonf {
  stop-color: var(--svg-color--ffd43e, #FFD43E);
}

.sautvobyf {
  fill: var(--svg-color--f4b616, #F4B616);
  d: path("M25.698 12.958c1.234-.64 2.598-.16 3.297.648c.945 1.094.744 2.918-.313 3.79c-.278.23-.617.49-.988.776c-1.035.797-2.315 1.783-3.207 2.802c-.793.845-1.248 1.513-1.583 2.114c-1.492-3.69-1.037-6.778-.367-8.437c.165.316.583.03.583.03c.37-.347 1.343-1.082 2.578-1.723");
}

.t5_l5rb5e {
  stop-color: var(--svg-color--e79330, #E79330);
  stop-opacity: 0;
}

.td79j7bjm {
  stop-color: var(--svg-color--ffe645, #FFE645);
  stop-opacity: 0;
}

.u0230sz1k {
  stop-color: var(--svg-color--ad690c, #AD690C);
}

.vs49h202c {
  stop-color: var(--svg-color--ffe542, #FFE542);
}

.vs98v1bqj {
  stop-color: var(--svg-color--f2a159, #F2A159);
  stop-opacity: 0;
}

.w14p2xbrq {
  d: path("M25.698 12.958c1.234-.64 2.598-.16 3.297.648c.945 1.094.744 2.918-.313 3.79c-.278.23-.617.49-.988.776c-1.035.797-2.315 1.783-3.207 2.802c-.793.845-1.248 1.513-1.583 2.114c-1.492-3.69-1.037-6.778-.367-8.437c.165.316.583.03.583.03c.37-.347 1.343-1.082 2.578-1.723");
}

.w7zguz1oo {
  d: path("M28.995 13.606c-.699-.808-2.063-1.289-3.297-.648c-1.235.64-2.208 1.376-2.578 1.723c0 0-.649.444-.649-.385v-9.26c0-1.672-1.125-2.969-2.625-2.969c-1.406 0-2.625 1.125-2.625 2.97l-.038 7.506H8.909V8.567c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.103 4.328 10.26 9.653 10.26c2.709 0 5.41-1.22 7.189-3.092c2.258-2.375 1.563-3.313 3.961-5.867c1.21-1.383 3.139-2.707 4.195-3.579c1.057-.87 1.258-2.695.313-3.789");
}

.x9idaudaq {
  stop-color: var(--svg-color--ffe948, #FFE948);
  stop-opacity: 0;
}

.xzcr82v6m {
  stop-color: var(--svg-color--e3961f, #E3961F);
  stop-opacity: 0;
}

</style>
