<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9tBcJc)"><path fill="url(#iOLAjzd)" class="ujydyib8d"/><path fill="url(#i6l0jZc)" class="ujydyib8d"/><path fill="url(#iEPl9ld)" class="ujydyib8d"/><path fill="url(#iXRRyde)" class="ujydyib8d"/></g><g filter="url(#i1yCe9b)"><path fill="url(#injTxdc)" class="ueos9yy2y"/></g><rect fill="url(#ipmA4Uc)" class="zys7f72ey"/><rect fill="url(#iKsIkbP)" class="qxrjxujji"/><path fill="url(#iAMSLEd)" class="tx2om3yfw"/><path fill="url(#iYAAqKc)" class="tx2om3yfw"/><path fill="url(#ijycD3d)" class="tx2om3yfw"/><path fill="url(#ieTtLCH)" class="tx2om3yfw"/><g filter="url(#i6NCmzb)"><rect fill="url(#il4VMYb)" class="zgqyibz6l"/><rect fill="url(#iswCNOD)" class="zgqyibz6l"/><rect fill="url(#iNDh7id)" class="zgqyibz6l"/></g><rect fill="url(#ivrz5oe)" class="ap-god9dl"/><rect fill="url(#i43vCdL)" class="ap-god9dl"/><rect fill="url(#ifU4tUb)" class="ap-god9dl"/><g filter="url(#i2qzUHd)"><rect class="xzgc6v8ua"/></g><g filter="url(#iDYV6kc)"><rect class="g-1v_8b0g"/></g><rect fill="url(#iBMwstc)" class="n9fokxb3a"/><rect fill="url(#ilg1Dod)" class="n9fokxb3a"/><rect fill="url(#i905u3b)" class="n9fokxb3a"/><defs><radialGradient id="i6l0jZc" cx="0" cy="0" r="1" gradientTransform="matrix(8.56555 0 0 4.57895 7.71 11.043)" gradientUnits="userSpaceOnUse"><stop class="kw38bbpct"/><stop offset="1" class="lsb_0cbyb"/></radialGradient><radialGradient id="iXRRyde" cx="0" cy="0" r="1" gradientTransform="matrix(-6.63519 0 0 -10.3302 16.544 19.184)" gradientUnits="userSpaceOnUse"><stop class="stxlyybsf"/><stop offset="1" class="nm1gjlbsz"/></radialGradient><radialGradient id="injTxdc" cx="0" cy="0" r="1" gradientTransform="matrix(4.68782 -7.19713 5.98956 3.90127 15.573 24.596)" gradientUnits="userSpaceOnUse"><stop class="mqmfu6bqp"/><stop offset="1" class="nikt4cb0f"/></radialGradient><radialGradient id="ipmA4Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.14807 -.05048 .00666 -1.33965 28.08 26.41)" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></radialGradient><radialGradient id="iKsIkbP" cx="0" cy="0" r="1" gradientTransform="matrix(4.4375 0 0 4.60372 29.625 27.045)" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset=".885" class="l9j77zbpn"/></radialGradient><radialGradient id="iAMSLEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1.8125 -5.24074 5.42145 12.967 6.38)" gradientUnits="userSpaceOnUse"><stop class="h8d0ebbky"/><stop offset=".858" class="xb6y8ac5a"/></radialGradient><radialGradient id="iYAAqKc" cx="0" cy="0" r="1" gradientTransform="rotate(142.344 8.33 7.288)scale(5.01297 1.89469)" gradientUnits="userSpaceOnUse"><stop class="rb-u_j9yu"/><stop offset="1" class="h-ox58bfs"/></radialGradient><radialGradient id="ijycD3d" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 8.932 6.449)scale(2.98951 1.97665)" gradientUnits="userSpaceOnUse"><stop class="ec28fgbcc"/><stop offset="1" class="gz26b2w_t"/></radialGradient><radialGradient id="ieTtLCH" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53125 0 0 -1.78125 17.752 10.813)" gradientUnits="userSpaceOnUse"><stop class="m7hw4ij-j"/><stop offset="1" class="j_b08ibpe"/></radialGradient><radialGradient id="il4VMYb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.84274 23.662 11.85)" gradientUnits="userSpaceOnUse"><stop class="eyqrs1b7e"/><stop offset="1" class="t9f54qzay"/></radialGradient><radialGradient id="iNDh7id" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -.25 .16715 3.48919 17.125 15.031)" gradientUnits="userSpaceOnUse"><stop class="ko77v0b6y"/><stop offset="1" class="inuuwhobl"/></radialGradient><radialGradient id="ivrz5oe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.20272 22.19 21.615)" gradientUnits="userSpaceOnUse"><stop class="s-dztxv8u"/><stop offset="1" class="owxgagoso"/></radialGradient><radialGradient id="ifU4tUb" cx="0" cy="0" r="1" gradientTransform="matrix(7.33922 0 0 2.25494 18.534 25.193)" gradientUnits="userSpaceOnUse"><stop class="k_lvphbuq"/><stop offset="1" class="g4mbeibfo"/></radialGradient><radialGradient id="iBMwstc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.11937 22.19 16.719)" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="t88yo5b1g"/></radialGradient><radialGradient id="i905u3b" cx="0" cy="0" r="1" gradientTransform="matrix(6.46207 0 0 3.4824 17.179 20.162)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="g3bv4db3k"/><stop offset="1" class="chxygu-et"/></radialGradient><linearGradient id="iOLAjzd" x1="14.36" x2="30.649" y1="31.333" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="s4dg0_shp"/><stop offset="1" class="zzph65bql"/></linearGradient><linearGradient id="iEPl9ld" x1="18.438" x2="18.438" y1="32.938" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="f4zlnbntg"/><stop offset="1" class="fu9oswbdl"/></linearGradient><linearGradient id="iswCNOD" x1="14.772" x2="19.102" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="l0q-w_4oj"/><stop offset="1" class="qgn0v40sz"/></linearGradient><linearGradient id="i43vCdL" x1="14.772" x2="19.102" y1="23.107" y2="23.107" gradientUnits="userSpaceOnUse"><stop class="e8cqipfnr"/><stop offset="1" class="sjy7fabtk"/></linearGradient><linearGradient id="ilg1Dod" x1="15.376" x2="19.102" y1="18.155" y2="18.155" gradientUnits="userSpaceOnUse"><stop class="z7t64jcbp"/><stop offset="1" class="a546jcb3w"/></linearGradient><filter id="i9tBcJc" width="27.371" height="28.636" x="2.689" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.45098 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2655"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.654902 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2655" result="effect2_innerShadow_20020_2655"/></filter><filter id="i1yCe9b" width="11.25" height="16.974" x="13.037" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2655" stdDeviation=".75"/></filter><filter id="i6NCmzb" width="10.338" height="6.078" x="15.376" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.588235 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2655"/></filter><filter id="i2qzUHd" width="8.315" height="2.188" x="16.308" y="13.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2655" stdDeviation=".375"/></filter><filter id="iDYV6kc" width="8.315" height="2.188" x="16.308" y="19.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2655" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:call-me-hand-medium-light" /></template>
<style>
.a546jcb3w {
  stop-color: var(--svg-color--be8a6c, #BE8A6C);
  stop-opacity: 0;
}

.ap-god9dl {
  width: 10.088px;
  height: 5.781px;
  x: 15.376px;
  y: 19.412px;
  rx: 2.891px;
}

.chxygu-et {
  stop-color: var(--svg-color--c1807f, #C1807F);
  stop-opacity: 0;
}

.e8cqipfnr {
  stop-color: var(--svg-color--be8873, #BE8873);
}

.ec28fgbcc {
  stop-color: var(--svg-color--ffd0a9, #FFD0A9);
}

.eyqrs1b7e {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
}

.f4zlnbntg {
  stop-color: var(--svg-color--bd788a, #BD788A);
}

.ft5dv1b6b {
  fill: none;
}

.fu9oswbdl {
  stop-color: var(--svg-color--bd788a, #BD788A);
  stop-opacity: 0;
}

.g-1v_8b0g {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 19.818px;
  fill: var(--svg-color--dc9461, #DC9461);
  rx: 0.344px;
}

.g3bv4db3k {
  stop-color: var(--svg-color--c1807f, #C1807F);
}

.g4mbeibfo {
  stop-color: var(--svg-color--b67186, #B67186);
  stop-opacity: 0;
}

.gz26b2w_t {
  stop-color: var(--svg-color--ffd0a9, #FFD0A9);
  stop-opacity: 0;
}

.h-ox58bfs {
  stop-color: var(--svg-color--dfa881, #DFA881);
  stop-opacity: 0;
}

.h8d0ebbky {
  stop-color: var(--svg-color--c59675, #C59675);
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.inuuwhobl {
  stop-color: var(--svg-color--c98f7e, #C98F7E);
  stop-opacity: 0;
}

.j_b08ibpe {
  stop-color: var(--svg-color--ebb996, #EBB996);
  stop-opacity: 0;
}

.k_lvphbuq {
  stop-color: var(--svg-color--b67186, #B67186);
}

.ko77v0b6y {
  stop-color: var(--svg-color--c98f7e, #C98F7E);
}

.kw38bbpct {
  stop-color: var(--svg-color--e2ae8d, #E2AE8D);
}

.l0q-w_4oj {
  stop-color: var(--svg-color--cb9b78, #CB9B78);
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lsb_0cbyb {
  stop-color: var(--svg-color--e2ae8d, #E2AE8D);
  stop-opacity: 0;
}

.m7hw4ij-j {
  stop-color: var(--svg-color--ebb996, #EBB996);
}

.mqmfu6bqp {
  stop-color: var(--svg-color--b07072, #B07072);
}

.n9fokxb3a {
  width: 10.088px;
  height: 5.563px;
  x: 15.376px;
  y: 14.599px;
  rx: 2.781px;
}

.nikt4cb0f {
  stop-color: var(--svg-color--915c46, #915C46);
}

.nm1gjlbsz {
  stop-color: var(--svg-color--be8a76, #BE8A76);
  stop-opacity: 0;
}

.owxgagoso {
  stop-color: var(--svg-color--d5a086, #D5A086);
}

.qgn0v40sz {
  stop-color: var(--svg-color--cb9b78, #CB9B78);
  stop-opacity: 0;
}

.qxrjxujji {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  rx: 2.898px;
}

.rb-u_j9yu {
  stop-color: var(--svg-color--dfa881, #DFA881);
}

.s-dztxv8u {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
}

.s4dg0_shp {
  stop-color: var(--svg-color--d89f8b, #D89F8B);
}

.sjy7fabtk {
  stop-color: var(--svg-color--be8873, #BE8873);
  stop-opacity: 0;
}

.stxlyybsf {
  stop-color: var(--svg-color--be8a76, #BE8A76);
}

.t88yo5b1g {
  stop-color: var(--svg-color--deab88, #DEAB88);
}

.t9f54qzay {
  stop-color: var(--svg-color--eab892, #EAB892);
}

.tx2om3yfw {
  d: path("m17.97 10.425l-.008-.005c.597-.853 1.968-2.82 2.508-3.703c.79-1.29.679-3.1-.581-4.073a2.76 2.76 0 0 0-1.69-.587a3 3 0 0 0-1.566.46c-.36.222-.7.528-1 .918c-2.388 3.7-5.187 5.899-6.611 6.504l-.035.02q-.196.087-.389.182c-.155.108-.203.22-.236.559c-.133 1.348 1.235 3.249 2.294 4.058c1.271.972 3.09.73 4.063-.542l2.967-3.39z");
}

.ueos9yy2y {
  d: path("M14.537 14.715c0-1.439 1.07-2.606 2.388-2.606H20.4c1.319 0 2.388 1.167 2.388 2.606c0 .942-.457 1.767-1.143 2.224c.683.43 1.143 1.235 1.143 2.157c0 .934-.471 1.747-1.168 2.173c.699.449 1.168 1.28 1.168 2.229c0 .75-.145 1.874-1.338 2.15l-4.543.435c-1.308 0-2.369-1.157-2.369-2.585c0-.95.47-1.78 1.169-2.23c-.697-.425-1.169-1.238-1.169-2.172c0-.922.46-1.727 1.143-2.157c-.685-.457-1.143-1.282-1.143-2.224");
}

.ujydyib8d {
  d: path("M17.962 10.42c3.188 1.826 5.35 5.346 5.35 9.273c0 1.603-.361 3.112-1.004 4.453h4.13c1.587 0 2.873 1.298 2.873 2.899s-1.286 2.898-2.872 2.898H14.084q-.33 0-.634-.008q-.21.008-.419.008c-6.874 0-10.342-4.551-10.342-10.281c0-4.284 2.608-8.067 6.298-9.703l.035-.02c1.424-.605 4.223-2.804 6.61-6.504c1.192-1.547 2.997-1.764 4.257-.791c1.26.972 1.371 2.784.581 4.073c-.54.883-1.911 2.85-2.508 3.703");
}

.xb6y8ac5a {
  stop-color: var(--svg-color--c59675, #C59675);
  stop-opacity: 0;
}

.xzgc6v8ua {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 14.395px;
  fill: var(--svg-color--dc9461, #DC9461);
  rx: 0.344px;
}

.z7t64jcbp {
  stop-color: var(--svg-color--be8a6c, #BE8A6C);
}

.zgqyibz6l {
  width: 10.088px;
  height: 5.828px;
  x: 15.376px;
  y: 9.568px;
  rx: 2.914px;
}

.zys7f72ey {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 2.898px;
}

.zzph65bql {
  stop-color: var(--svg-color--e4b28c, #E4B28C);
}

</style>
