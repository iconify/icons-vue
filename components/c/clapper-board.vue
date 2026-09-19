<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivAbw0D)" class="i985plbns"/><path fill="url(#ifeGrnE)" class="i985plbns"/><path fill="url(#iiWTkFQ)" class="i985plbns"/><g filter="url(#i1bHpcB)"><path fill="url(#i3LT0jd)" class="grey-cb_p"/></g><path fill="url(#iCqx4jc)" class="grey-cb_p"/><path fill="url(#iJ5bQpe)" class="m3v21_oli"/><path fill="url(#ibr5evb)" class="m3v21_oli"/><g filter="url(#ijOTnet)"><path fill="url(#iElRKXN)" class="m96fwdbrq"/></g><path fill="url(#iYCrMGc)" class="v1mmyvbgt"/><path fill="url(#if1vmbb)" class="v1mmyvbgt"/><g filter="url(#itMhxxd)"><path fill="url(#i4Ss5fi)" class="zaq_msabr"/></g><g filter="url(#idVjukb)"><path class="kkh25jxmp"/></g><g filter="url(#iIcDwad)"><path class="lwxxy8bzr"/></g><g filter="url(#iTjxPHb)"><path stroke="url(#iZC49Nc)" class="q1mdj8z4w"/></g><g filter="url(#iQIZuEc)"><path stroke="url(#i5UQkIc)" class="a3254-bgg"/></g><g filter="url(#iZS5PPb)"><path class="ntwerzued"/></g><g filter="url(#i3hU1Hc)"><path class="td15981ed"/></g><g filter="url(#igjuDNb)"><path class="ytf83v_9q"/></g><g filter="url(#iKXA40P)"><path class="ou1s1yjiv"/></g><defs><linearGradient id="ivAbw0D" x1="4.508" x2="6.851" y1="22.219" y2="22.219" gradientUnits="userSpaceOnUse"><stop class="xnbg9jb8e"/><stop offset="1" class="ztb1ygtms"/></linearGradient><linearGradient id="ifeGrnE" x1="5.789" x2="5.789" y1="30.094" y2="28.062" gradientUnits="userSpaceOnUse"><stop class="rk_kfpqcr"/><stop offset="1" class="rtxoz5b1u"/></linearGradient><linearGradient id="iiWTkFQ" x1="6.054" x2="6.054" y1="16.719" y2="17.344" gradientUnits="userSpaceOnUse"><stop class="o5fwdsb-d"/><stop offset="1" class="fg9adybhd"/></linearGradient><linearGradient id="i3LT0jd" x1="17.285" x2="17.285" y1="17.892" y2="29.873" gradientUnits="userSpaceOnUse"><stop class="xjuarwb1k"/><stop offset="1" class="si0jwb6ri"/></linearGradient><linearGradient id="iCqx4jc" x1="6.645" x2="7.414" y1="26.656" y2="26.656" gradientUnits="userSpaceOnUse"><stop class="r4gjykbre"/><stop offset="1" class="k6tyko6_f"/></linearGradient><linearGradient id="iJ5bQpe" x1="4.476" x2="6.601" y1="16.438" y2="14.344" gradientUnits="userSpaceOnUse"><stop class="p82eu3gho"/><stop offset="1" class="nolu8f0gv"/></linearGradient><linearGradient id="ibr5evb" x1="6.383" x2="6.383" y1="16.719" y2="16.281" gradientUnits="userSpaceOnUse"><stop class="wv_pevrcv"/><stop offset="1" class="kinwlo8wg"/></linearGradient><linearGradient id="iElRKXN" x1="17.285" x2="17.285" y1="14.344" y2="16.719" gradientUnits="userSpaceOnUse"><stop class="c9aot247l"/><stop offset="1" class="vwiq6wsjs"/></linearGradient><linearGradient id="iYCrMGc" x1="5.664" x2="4.789" y1="11.688" y2="7.594" gradientUnits="userSpaceOnUse"><stop class="iv7r6wv6h"/><stop offset="1" class="i3ogpmbkr"/></linearGradient><linearGradient id="if1vmbb" x1="5.57" x2="5.976" y1="6.969" y2="8.781" gradientUnits="userSpaceOnUse"><stop class="iiua1j3mt"/><stop offset="1" class="udlr58bxb"/></linearGradient><linearGradient id="i4Ss5fi" x1="19.695" x2="18.601" y1="3.812" y2="8.031" gradientUnits="userSpaceOnUse"><stop class="ntw_n9b_i"/><stop offset="1" class="k3od6m6pv"/></linearGradient><linearGradient id="iZC49Nc" x1="27.742" x2="7.429" y1="17.094" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="pjsjupbnv"/><stop offset="1" class="nqzag0b6s"/></linearGradient><linearGradient id="i5UQkIc" x1="27.625" x2="7.312" y1="13.219" y2="13.219" gradientUnits="userSpaceOnUse"><stop class="mx9njmfuv"/><stop offset="1" class="opv7zhboz"/></linearGradient><filter id="i1bHpcB" width="21.629" height="13.654" x="6.545" y="16.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.215686 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.35"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.478431 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.219608 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_20191" result="effect3_innerShadow_18_20191"/></filter><filter id="ijOTnet" width="21.429" height="4.136" x="6.645" y="12.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.301961 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/></filter><filter id="itMhxxd" width="22.04" height="9.32" x="5.547" y="2.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.541176 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.368627 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_20191" result="effect3_innerShadow_18_20191"/></filter><filter id="idVjukb" width="9.142" height="4.735" x="6.759" y="5.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.741176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.741176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/></filter><filter id="iIcDwad" width="9.157" height="4.74" x="16.1" y="3.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.741176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.741176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/></filter><filter id="iTjxPHb" width="20.925" height=".55" x="6.904" y="16.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20191" stdDeviation=".075"/></filter><filter id="iQIZuEc" width="21.098" height=".45" x="6.837" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20191" stdDeviation=".075"/></filter><filter id="iZS5PPb" width="8.428" height="4.136" x="7.831" y="12.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.678431 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.721569 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/></filter><filter id="i3hU1Hc" width="8.428" height="4.136" x="17.633" y="12.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.678431 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".3"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.721569 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20191" result="effect2_innerShadow_18_20191"/></filter><filter id="igjuDNb" width="4.966" height=".45" x="11.001" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20191" stdDeviation=".075"/></filter><filter id="iKXA40P" width="4.966" height=".45" x="20.814" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20191" stdDeviation=".075"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clapper-board" /></template>
<style>
.a3254-bgg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.062 13.219h20.649");
}

.c9aot247l {
  stop-color: var(--svg-color--8f6dbd, #8F6DBD);
}

.fg9adybhd {
  stop-color: var(--svg-color--45374f, #45374F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.grey-cb_p {
  d: path("M6.645 16.97a.25.25 0 0 1 .25-.25h20.78a.25.25 0 0 1 .25.25v11.003a1.9 1.9 0 0 1-1.9 1.9H8.544a1.9 1.9 0 0 1-1.9-1.9z");
}

.i3ogpmbkr {
  stop-color: var(--svg-color--514257, #514257);
}

.i985plbns {
  d: path("M4.145 16.97a.25.25 0 0 1 .25-.25h20.78a.25.25 0 0 1 .25.25v11.003a1.9 1.9 0 0 1-1.9 1.9H6.044a1.9 1.9 0 0 1-1.9-1.9z");
}

.iiua1j3mt {
  stop-color: var(--svg-color--947397, #947397);
}

.iv7r6wv6h {
  stop-color: var(--svg-color--483751, #483751);
}

.k3od6m6pv {
  stop-color: var(--svg-color--8a6eb8, #8A6EB8);
}

.k6tyko6_f {
  stop-color: var(--svg-color--5f5691, #5F5691);
  stop-opacity: 0;
}

.kinwlo8wg {
  stop-color: var(--svg-color--3d2e49, #3D2E49);
  stop-opacity: 0;
}

.kkh25jxmp {
  fill: var(--svg-color--cacbff, #CACBFF);
  d: path("m15.75 8.919l-4.704 1.22a1 1 0 0 0-.277-.301l-.013-.01a396 396 0 0 0-3.515-2.719a.9.9 0 0 0-.332-.164a2 2 0 0 1 .287-.098l4.412-1.143c.122.046.215.112.281.163c.427.33 1.052.81 1.654 1.271a169 169 0 0 1 1.772 1.366c.267.197.38.328.435.415");
}

.lwxxy8bzr {
  fill: var(--svg-color--cacbff, #CACBFF);
  d: path("M25.107 6.493L20.39 7.716c-.094-.17-.228-.3-.305-.357c-1.03-.794-3.159-2.434-3.421-2.64a1.3 1.3 0 0 0-.413-.219l4.722-1.224c.178.087.33.206.459.306l.005.004c1.037.807 3.172 2.466 3.422 2.64c.142.1.215.194.25.267");
}

.m3v21_oli {
  d: path("M4.145 13.133a.25.25 0 0 1 .25-.25h20.78a.25.25 0 0 1 .25.25v3.336a.25.25 0 0 1-.25.25H4.394a.25.25 0 0 1-.25-.25z");
}

.m96fwdbrq {
  d: path("M6.645 13.133a.25.25 0 0 1 .25-.25h20.78a.25.25 0 0 1 .25.25v3.336a.25.25 0 0 1-.25.25H6.894a.25.25 0 0 1-.25-.25z");
}

.mx9njmfuv {
  stop-color: var(--svg-color--9474bc, #9474BC);
}

.nolu8f0gv {
  stop-color: var(--svg-color--3f3148, #3F3148);
}

.nqzag0b6s {
  stop-color: var(--svg-color--786585, #786585);
}

.ntw_n9b_i {
  stop-color: var(--svg-color--8d74ba, #8D74BA);
}

.ntwerzued {
  fill: var(--svg-color--cdcdff, #CDCDFF);
  d: path("M7.981 16.72c.078-.043.174-.114.276-.227c.206-.226 1.906-2.234 2.73-3.21a1.2 1.2 0 0 0 .2-.4h4.922c-.051.115-.139.28-.29.469c-.172.213-1.846 2.183-2.661 3.141a1.7 1.7 0 0 1-.257.226z");
}

.o5fwdsb-d {
  stop-color: var(--svg-color--1e0f2a, #1E0F2A);
}

.opv7zhboz {
  stop-color: var(--svg-color--9c81c5, #9C81C5);
}

.ou1s1yjiv {
  stroke: var(--svg-color--d3d4ff, #D3D4FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M21.039 13.219h4.515");
}

.p82eu3gho {
  stop-color: var(--svg-color--45374f, #45374F);
}

.pjsjupbnv {
  stop-color: var(--svg-color--857498, #857498);
}

.q1mdj8z4w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.18 17.094h20.374");
}

.r4gjykbre {
  stop-color: var(--svg-color--5f5691, #5F5691);
}

.rk_kfpqcr {
  stop-color: var(--svg-color--5f75a6, #5F75A6);
}

.rtxoz5b1u {
  stop-color: var(--svg-color--443c61, #443C61);
  stop-opacity: 0;
}

.si0jwb6ri {
  stop-color: var(--svg-color--8180c8, #8180C8);
}

.td15981ed {
  fill: var(--svg-color--cdcdff, #CDCDFF);
  d: path("M17.783 16.72c.078-.043.173-.114.276-.227a384 384 0 0 0 2.729-3.21a1.2 1.2 0 0 0 .2-.4h4.923c-.052.115-.139.28-.29.469c-.173.213-1.846 2.183-2.662 3.141a1.7 1.7 0 0 1-.257.226z");
}

.udlr58bxb {
  stop-color: var(--svg-color--5b4860, #5B4860);
  stop-opacity: 0;
}

.v1mmyvbgt {
  d: path("M3.668 9.828A2 2 0 0 1 5.102 7.39L22.42 2.9a2 2 0 0 1 2.438 1.435l.477 1.84a.25.25 0 0 1-.179.305L4.45 11.848a.25.25 0 0 1-.305-.179z");
}

.vwiq6wsjs {
  stop-color: var(--svg-color--8661b9, #8661B9);
}

.wv_pevrcv {
  stop-color: var(--svg-color--22112e, #22112E);
}

.xjuarwb1k {
  stop-color: var(--svg-color--7b638e, #7B638E);
}

.xnbg9jb8e {
  stop-color: var(--svg-color--473850, #473850);
}

.ytf83v_9q {
  stroke: var(--svg-color--d3d4ff, #D3D4FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.226 13.219h4.516");
}

.zaq_msabr {
  d: path("M5.762 9.285a2 2 0 0 1 1.434-2.438l17.318-4.49a2 2 0 0 1 2.438 1.435l.477 1.84a.25.25 0 0 1-.179.305L6.544 11.305a.25.25 0 0 1-.305-.179z");
}

.ztb1ygtms {
  stop-color: var(--svg-color--3f314a, #3F314A);
}

</style>
