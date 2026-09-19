<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iee9mXb)"><path fill="url(#iww4jWd)" class="p73wcmbjw"/><path fill="url(#ituyBcd)" class="p73wcmbjw"/></g><path fill="url(#ivEMCsb)" class="p73wcmbjw"/><g filter="url(#iibd1Zb)"><path class="aoz44_b7g"/></g><g filter="url(#iwK9UwH)"><path class="gov347b8d"/></g><g filter="url(#iA8wq3e)"><path class="ywp09fwsz"/></g><g filter="url(#iegDB9c)"><path class="qc832mb6e"/></g><g filter="url(#inhrQPd)"><path class="o96x9xobd"/></g><g filter="url(#iLR5sCc)"><path class="vpn8_cidk"/></g><path fill="url(#iktNIBc)" class="oyc55krxm"/><path fill="url(#itBPOxb)" class="oyc55krxm"/><path fill="url(#iSawfPd)" class="qq_h7f0wy"/><path fill="url(#ipFITqd)" class="qq_h7f0wy"/><path fill="url(#iAsCIod)" class="qq_h7f0wy"/><path fill="url(#iu4XNGc)" class="qq_h7f0wy"/><path fill="url(#ikovGFb)" class="qq_h7f0wy"/><g filter="url(#ix1FSWb)"><path class="mt3pavbsf"/></g><g filter="url(#iTA2Qpb)"><path class="v5h6sib6v"/></g><g filter="url(#iaGEycd)"><path class="l6uo29b0s"/></g><g filter="url(#iSlMwld)"><path class="ip8ejuoby"/></g><defs><filter id="iee9mXb" width="28.8" height="28.799" x="1.694" y="1.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2267"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.341176 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2267" result="effect2_innerShadow_18_2267"/></filter><filter id="iibd1Zb" width="3.5" height="3.5" x="12.594" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2267" stdDeviation=".125"/></filter><filter id="iwK9UwH" width="3.5" height="3.5" x="10.094" y="17.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2267" stdDeviation=".125"/></filter><filter id="iA8wq3e" width="3.5" height="3.5" x="15.094" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2267" stdDeviation=".125"/></filter><filter id="iegDB9c" width="3.5" height="3.5" x="17.594" y="10.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2267" stdDeviation=".125"/></filter><filter id="inhrQPd" width="14.425" height="14.425" x="15.291" y="2.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2267" stdDeviation=".25"/></filter><filter id="iLR5sCc" width="14.687" height="14.469" x="2.189" y="15.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2267" stdDeviation=".25"/></filter><filter id="ix1FSWb" width="3.9" height="3.9" x="12.644" y="14.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.909804 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2267"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.568627 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2267" result="effect2_innerShadow_18_2267"/></filter><filter id="iTA2Qpb" width="3.9" height="3.9" x="10.144" y="17.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.909804 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2267"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.568627 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2267" result="effect2_innerShadow_18_2267"/></filter><filter id="iaGEycd" width="3.9" height="3.9" x="15.144" y="12.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.909804 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2267"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.568627 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2267" result="effect2_innerShadow_18_2267"/></filter><filter id="iSlMwld" width="3.9" height="3.9" x="17.644" y="9.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.909804 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2267"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.568627 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2267" result="effect2_innerShadow_18_2267"/></filter><radialGradient id="ituyBcd" cx="0" cy="0" r="1" gradientTransform="matrix(7.02346 25.49818 -25.49943 7.0238 11.654 3.869)" gradientUnits="userSpaceOnUse"><stop offset=".791" class="ixewwcjzb"/><stop offset="1" class="lbrs9jbnb"/></radialGradient><radialGradient id="ivEMCsb" cx="0" cy="0" r="1" gradientTransform="rotate(135 15.27 7.773)scale(22.5567 4.896)" gradientUnits="userSpaceOnUse"><stop class="a_teo_bia"/><stop offset="1" class="oeqov15lc"/></radialGradient><radialGradient id="iktNIBc" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.585 9.805)scale(5.10057 9.48153)" gradientUnits="userSpaceOnUse"><stop class="pqm_lpbeq"/><stop offset="1" class="kpf9k5tdf"/></radialGradient><radialGradient id="iSawfPd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.41385 3.73475 -6.94254 -8.20492 13.513 24.134)" gradientUnits="userSpaceOnUse"><stop class="y1n5-2b4u"/><stop offset="1" class="kpf9k5tdf"/><stop offset="1" class="ai9-2ku0o"/></radialGradient><radialGradient id="ikovGFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3532 .37281 -3.68036 -3.48668 14.172 25.504)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="t8brqrbxt"/><stop offset="1" class="s5p_7wkjk"/></radialGradient><linearGradient id="iww4jWd" x1="23.216" x2="4.122" y1="7.72" y2="28.298" gradientUnits="userSpaceOnUse"><stop class="hzx5onbtd"/><stop offset="1" class="mhv8z5b-l"/></linearGradient><linearGradient id="itBPOxb" x1="21.832" x2="22.11" y1="9.572" y2="9.294" gradientUnits="userSpaceOnUse"><stop class="gzyihdbrc"/><stop offset="1" class="m_6wqxb1k"/></linearGradient><linearGradient id="ipFITqd" x1="1.048" x2="8.517" y1="14.876" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="oro0uwl6w"/><stop offset="1" class="ppfdzg2qp"/></linearGradient><linearGradient id="iAsCIod" x1="7.813" x2="8.082" y1="23.563" y2="23.294" gradientUnits="userSpaceOnUse"><stop class="h725jwmag"/><stop offset="1" class="lh36dyosx"/></linearGradient><linearGradient id="iu4XNGc" x1="15.356" x2="14.532" y1="29.663" y2="27.286" gradientUnits="userSpaceOnUse"><stop class="vakhc8a6m"/><stop offset="1" class="u64cbb7-d"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:american-football" /></template>
<style>
.a_teo_bia {
  stop-color: var(--svg-color--ab8072, #AB8072);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.aoz44_b7g {
  stroke: var(--svg-color--784047, #784047);
  stroke-linecap: round;
  d: path("m13.344 16l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.gov347b8d {
  stroke: var(--svg-color--784047, #784047);
  stroke-linecap: round;
  d: path("m10.844 18.5l2 2");
}

.gzyihdbrc {
  stop-color: var(--svg-color--998fa0, #998FA0);
}

.h725jwmag {
  stop-color: var(--svg-color--9778b6, #9778B6);
}

.hzx5onbtd {
  stop-color: var(--svg-color--8c5949, #8C5949);
}

.ip8ejuoby {
  fill: var(--svg-color--dad4e6, #DAD4E6);
  d: path("M19.124 10.22a.75.75 0 0 0-1.06 1.061zm.94 3.061a.75.75 0 1 0 1.06-1.06zm-2-2l2 2l1.06-1.06l-2-2z");
}

.ixewwcjzb {
  stop-color: var(--svg-color--743b6c, #743B6C);
  stop-opacity: 0;
}

.kpf9k5tdf {
  stop-color: var(--svg-color--b8b8b8, #B8B8B8);
}

.l6uo29b0s {
  stroke: var(--svg-color--dad4e6, #DAD4E6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.094 13.25l2 2");
}

.lbrs9jbnb {
  stop-color: var(--svg-color--743b6c, #743B6C);
}

.lh36dyosx {
  stop-color: var(--svg-color--9778b6, #9778B6);
  stop-opacity: 0;
}

.m_6wqxb1k {
  stop-color: var(--svg-color--998fa0, #998FA0);
  stop-opacity: 0;
}

.mhv8z5b-l {
  stop-color: var(--svg-color--6c4140, #6C4140);
}

.mt3pavbsf {
  stroke: var(--svg-color--dad4e6, #DAD4E6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.594 15.75l2 2");
}

.o96x9xobd {
  fill: var(--svg-color--6d3940, #6D3940);
  d: path("M28.328 16.019c.38-1 .678-2.04.888-3.11L18.9 2.594c-1.07.21-2.11.508-3.11.888z");
}

.oeqov15lc {
  stop-color: var(--svg-color--ab8072, #AB8072);
  stop-opacity: 0;
}

.oro0uwl6w {
  stop-color: var(--svg-color--8d8b90, #8D8B90);
}

.oyc55krxm {
  d: path("M28.771 16.378c.403-1.063.72-2.166.942-3.301L18.767 2.13a20.4 20.4 0 0 0-3.301.942z");
}

.p73wcmbjw {
  d: path("M29.822 5.775c2.25 13.92-9.782 25.96-23.705 23.7a4.52 4.52 0 0 1-3.75-3.75c-2.252-13.92 9.78-25.96 23.703-23.7c1.92.31 3.43 1.82 3.75 3.75");
}

.ppfdzg2qp {
  stop-color: var(--svg-color--8d8b90, #8D8B90);
  stop-opacity: 0;
}

.pqm_lpbeq {
  stop-color: var(--svg-color--f5f1f8, #F5F1F8);
}

.qc832mb6e {
  fill: var(--svg-color--784047, #784047);
  d: path("M18.698 10.646a.5.5 0 0 0-.708.708zm1.292 2.708a.5.5 0 0 0 .708-.708zm-2-2l2 2l.708-.708l-2-2z");
}

.qq_h7f0wy {
  d: path("M13.706 29.312a20.4 20.4 0 0 0 3.263-.98L3.512 14.877a20.4 20.4 0 0 0-.98 3.263z");
}

.s5p_7wkjk {
  stop-color: var(--svg-color--c3bcd9, #C3BCD9);
  stop-opacity: 0;
}

.t8brqrbxt {
  stop-color: var(--svg-color--c3bcd9, #C3BCD9);
}

.u64cbb7-d {
  stop-color: var(--svg-color--af87d2, #AF87D2);
  stop-opacity: 0;
}

.v5h6sib6v {
  stroke: var(--svg-color--dad4e6, #DAD4E6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.094 18.25l2 2");
}

.vakhc8a6m {
  stop-color: var(--svg-color--af87d2, #AF87D2);
}

.vpn8_cidk {
  fill: var(--svg-color--6d3940, #6D3940);
  d: path("M13.078 29.094c1.065-.224 1.313-1.156 3.297-.71L3.617 15.626c1.243 2.437 1.352 2.797-.928 3.093z");
}

.y1n5-2b4u {
  stop-color: var(--svg-color--bfa9d8, #BFA9D8);
}

.ywp09fwsz {
  stroke: var(--svg-color--784047, #784047);
  stroke-linecap: round;
  d: path("m15.844 13.5l2 2");
}

</style>
