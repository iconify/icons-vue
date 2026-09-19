<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQd5hmc)" class="ha59rybrh"/><path fill="url(#ifnhGQc)" class="nt4w8shux"/><path fill="url(#iDUFlAe)" class="nt4w8shux"/><g filter="url(#iCasXtL)"><path fill="url(#iReQjZd)" class="vzeq807cd"/></g><path fill="url(#iD0cMxc)" class="vzeq807cd"/><path fill="url(#ihEx1Vc)" class="vzeq807cd"/><path fill="url(#idT5wec)" class="vzeq807cd"/><g filter="url(#i3Oe1De)"><rect transform="rotate(44.98 19.609 19.015)" class="thc84v-8e"/></g><rect fill="url(#iiUdHKc)" class="ic61hgpok"/><rect fill="url(#iupWisd)" transform="rotate(90 7.32 13.498)" class="wr0sd4_lk"/><g filter="url(#i2r3cxc)"><path fill="url(#i6zpuod)" class="gqs0v9b-k"/></g><rect fill="url(#iVg4Izc)" transform="rotate(135 9.625 8.723)" class="mm0p1hldp"/><g filter="url(#ixg1XYc)"><path fill="url(#iU3JHxc)" transform="rotate(45 17.843 8.002)" class="gz7igccqe"/></g><g filter="url(#iWRQ7sb)"><rect fill="url(#iQBoDbc)" class="w93dm6yaz"/></g><g filter="url(#iuMHNxb)"><rect fill="url(#iGmSGPe)" transform="rotate(-90 2.308 14.29)" class="etsccj02i"/></g><g filter="url(#ijkkgId)"><rect fill="url(#iMuMKMc)" transform="rotate(-45 5.19 5.352)" class="a3ww5obon"/></g><defs><linearGradient id="iReQjZd" x1="25.013" x2="20.169" y1="21.348" y2="26.098" gradientUnits="userSpaceOnUse"><stop class="b4w31cc7z"/><stop offset=".898" class="vh5fs5b-d"/></linearGradient><linearGradient id="ihEx1Vc" x1="28.607" x2="25.7" y1="29.254" y2="26.504" gradientUnits="userSpaceOnUse"><stop class="rl5ml-4ju"/><stop offset="1" class="ei9zqibwd"/></linearGradient><linearGradient id="idT5wec" x1="15.794" x2="16.607" y1="21.473" y2="22.035" gradientUnits="userSpaceOnUse"><stop offset=".254" class="fhgmeab3h"/><stop offset="1" class="z9qm8wbqc"/></linearGradient><linearGradient id="iiUdHKc" x1="13.699" x2="13.699" y1="2.332" y2="7.91" gradientUnits="userSpaceOnUse"><stop class="a30nnuz6x"/><stop offset="1" class="ichylqbed"/></linearGradient><linearGradient id="iupWisd" x1="8.11" x2="8.11" y1="13.498" y2="19.076" gradientUnits="userSpaceOnUse"><stop class="a30nnuz6x"/><stop offset="1" class="ichylqbed"/></linearGradient><linearGradient id="i6zpuod" x1="18.607" x2="12.294" y1="8.223" y2="14.973" gradientUnits="userSpaceOnUse"><stop class="tbrqztb8c"/><stop offset="1" class="ejfdg3bwh"/></linearGradient><linearGradient id="iVg4Izc" x1="10.415" x2="10.415" y1="8.723" y2="14.676" gradientUnits="userSpaceOnUse"><stop class="a30nnuz6x"/><stop offset="1" class="ichylqbed"/></linearGradient><linearGradient id="iU3JHxc" x1="18.76" x2="18.764" y1="7.386" y2="15.054" gradientUnits="userSpaceOnUse"><stop class="g9scdukwd"/><stop offset=".421" class="gzfucwb4j"/><stop offset=".604" class="gzfucwb4j"/><stop offset="1" class="g9scdukwd"/></linearGradient><linearGradient id="iQBoDbc" x1="13.981" x2="13.981" y1="2.731" y2="8.891" gradientUnits="userSpaceOnUse"><stop class="v_vwiu8iu"/><stop offset="1" class="x_td27jji"/></linearGradient><linearGradient id="iGmSGPe" x1="2.59" x2="2.59" y1="15.244" y2="19.306" gradientUnits="userSpaceOnUse"><stop class="hwpxp6bqc"/><stop offset="1" class="s49b2obup"/></linearGradient><linearGradient id="iMuMKMc" x1="5.472" x2="5.472" y1="5.352" y2="11.94" gradientUnits="userSpaceOnUse"><stop class="v_vwiu8iu"/><stop offset="1" class="x_td27jji"/></linearGradient><filter id="iCasXtL" width="14.34" height="14.309" x="15.335" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.878431 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20541"/></filter><filter id="i3Oe1De" width="3.841" height="3.84" x="18.176" y="19.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.686275 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_20541"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_20541" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.815686 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_20541"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.956863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_20541" result="effect3_innerShadow_18_20541"/></filter><filter id="i2r3cxc" width="12.606" height="12.606" x="6.962" y="7.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.345098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20541"/></filter><filter id="ixg1XYc" width="6.887" height="6.887" x="12.557" y="7.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20541" stdDeviation=".15"/></filter><filter id="iWRQ7sb" width="1.364" height="5.246" x="13.299" y="2.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20541" stdDeviation=".2"/></filter><filter id="iuMHNxb" width="5.246" height="1.364" x="1.908" y="13.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20541" stdDeviation=".2"/></filter><filter id="ijkkgId" width="4.527" height="4.527" x="4.807" y="4.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20541" stdDeviation=".25"/></filter><radialGradient id="iQd5hmc" cx="0" cy="0" r="1" gradientTransform="rotate(135 5.18 8.061)scale(7.6014 1.54181)" gradientUnits="userSpaceOnUse"><stop class="b_n6e9bav"/><stop offset="1" class="cx7zn7t4o"/></radialGradient><radialGradient id="ifnhGQc" cx="0" cy="0" r="1" gradientTransform="rotate(45 -6.354 26.603)scale(10.8497 9.21449)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="vpfqxm9fd"/><stop offset="1" class="t4bbqg85n"/></radialGradient><radialGradient id="iDUFlAe" cx="0" cy="0" r="1" gradientTransform="rotate(-8.455 117.088 -68.37)scale(10.4144)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="plh0s5bpt"/><stop offset="1" class="t_vqt9p6v"/></radialGradient><radialGradient id="iD0cMxc" cx="0" cy="0" r="1" gradientTransform="matrix(.48437 .5 -1.79219 1.73618 20.45 16.973)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="ulknrccbd"/><stop offset="1" class="vvdt1rz_m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flashlight" /></template>
<style>
.a30nnuz6x {
  stop-color: var(--svg-color--ffc327, #FFC327);
}

.a3ww5obon {
  width: 0.564px;
  height: 4.755px;
  x: 5.191px;
  y: 5.352px;
  rx: 0.282px;
}

.b_n6e9bav {
  stop-color: var(--svg-color--ffc44b, #FFC44B);
}

.b4w31cc7z {
  stop-color: var(--svg-color--e7e6e9, #E7E6E9);
}

.cx7zn7t4o {
  stop-color: var(--svg-color--e9b12f, #E9B12F);
}

.ei9zqibwd {
  stop-color: var(--svg-color--cac1d4, #CAC1D4);
  stop-opacity: 0;
}

.ejfdg3bwh {
  stop-color: var(--svg-color--3e3448, #3E3448);
}

.etsccj02i {
  width: 0.564px;
  height: 4.446px;
  x: 2.308px;
  y: 14.289px;
  rx: 0.282px;
}

.fhgmeab3h {
  stop-color: var(--svg-color--b8aac3, #B8AAC3);
}

.ft5dv1b6b {
  fill: none;
}

.g9scdukwd {
  stop-color: var(--svg-color--6b6374, #6B6374);
  stop-opacity: 0;
}

.gqs0v9b-k {
  d: path("M7.225 19.092a.9.9 0 0 1 0-1.273l9.993-9.993a.9.9 0 0 1 1.273 0l.813.813a.9.9 0 0 1 0 1.273l-9.993 9.993a.9.9 0 0 1-1.272 0z");
}

.gz7igccqe {
  d: path("M17.843 8.002h1.84v7.051h-1.84z");
}

.gzfucwb4j {
  stop-color: var(--svg-color--6b6374, #6B6374);
}

.ha59rybrh {
  d: path("M15.767 16.118c-3.003 3.003-6.481 4.394-7.768 3.106c-1.288-1.287-.526-4.135 2.935-7.595c3.578-3.579 6.26-4.303 7.548-3.016c1.287 1.288.287 4.503-2.715 7.505");
}

.hwpxp6bqc {
  stop-color: var(--svg-color--ffc538, #FFC538);
}

.ic61hgpok {
  width: 1.58px;
  height: 5.578px;
  x: 12.909px;
  y: 2.332px;
  rx: 0.79px;
}

.ichylqbed {
  stop-color: var(--svg-color--feb813, #FEB813);
}

.mm0p1hldp {
  width: 1.58px;
  height: 5.953px;
  x: 9.625px;
  y: 8.723px;
  rx: 0.79px;
}

.nt4w8shux {
  d: path("M8.17 19.004L18.45 8.723l1.047 1.047A7.27 7.27 0 1 1 9.216 20.05z");
}

.plh0s5bpt {
  stop-color: var(--svg-color--dedddf, #DEDDDF);
  stop-opacity: 0;
}

.rl5ml-4ju {
  stop-color: var(--svg-color--bcb1c8, #BCB1C8);
}

.s49b2obup {
  stop-color: var(--svg-color--ffc538, #FFC538);
  stop-opacity: 0;
}

.t_vqt9p6v {
  stop-color: var(--svg-color--dedddf, #DEDDDF);
}

.t4bbqg85n {
  stop-color: var(--svg-color--b8a9c7, #B8A9C7);
}

.tbrqztb8c {
  stop-color: var(--svg-color--584965, #584965);
}

.thc84v-8e {
  width: 3.327px;
  height: 1.666px;
  x: 19.609px;
  y: 19.015px;
  fill: var(--svg-color--eee6f6, #EEE6F6);
  rx: 0.833px;
}

.ulknrccbd {
  stop-color: var(--svg-color--e6e2e9, #E6E2E9);
}

.v_vwiu8iu {
  stop-color: var(--svg-color--ffd956, #FFD956);
}

.vh5fs5b-d {
  stop-color: var(--svg-color--b6a9c3, #B6A9C3);
}

.vpfqxm9fd {
  stop-color: var(--svg-color--e7e4e9, #E7E4E9);
}

.vvdt1rz_m {
  stop-color: var(--svg-color--e6e2e9, #E6E2E9);
  stop-opacity: 0;
}

.vzeq807cd {
  d: path("m15.59 21.959l-.104.135a.8.8 0 0 1 .425.12l6.739 6.74a4.116 4.116 0 0 0 5.82-5.821l-6.8-6.8c-.103-.1-.12-.245-.122-.333z");
}

.w93dm6yaz {
  width: 0.564px;
  height: 4.446px;
  x: 13.699px;
  y: 2.731px;
  rx: 0.282px;
}

.wr0sd4_lk {
  width: 1.58px;
  height: 5.578px;
  x: 7.32px;
  y: 13.498px;
  rx: 0.79px;
}

.x_td27jji {
  stop-color: var(--svg-color--ffd956, #FFD956);
  stop-opacity: 0;
}

.z9qm8wbqc {
  stop-color: var(--svg-color--bbacc9, #BBACC9);
  stop-opacity: 0;
}

</style>
