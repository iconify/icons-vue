<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iL2ltIb)"><rect fill="url(#i0DTb1b)" class="mn0__lb4b"/></g><rect fill="url(#i8XipIe)" class="mn0__lb4b"/><g filter="url(#i75Rj7d)"><path class="ybktwea4p"/></g><g filter="url(#i2hvu2s)"><path class="vhr_jbbnt"/></g><g filter="url(#i6EtGUC)"><path clip-rule="evenodd" class="m_f__4-zd"/></g><g filter="url(#iKiFa3d)"><path clip-rule="evenodd" class="ukf8cjbkk"/></g><defs><filter id="iL2ltIb" width="32" height="32" x="0" y="0" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21723"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-2" dy="2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.941176 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21723" result="effect2_innerShadow_18_21723"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.858824 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21723" result="effect3_innerShadow_18_21723"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.470588 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_21723" result="effect4_innerShadow_18_21723"/></filter><filter id="i75Rj7d" width="9.09" height="13.48" x="4.062" y="4.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21723" stdDeviation=".5"/></filter><filter id="i2hvu2s" width="7.39" height="11.78" x="5.062" y="4.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.847059 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21723"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.94902 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21723" result="effect2_innerShadow_18_21723"/></filter><filter id="i6EtGUC" width="23.797" height="15.703" x="4.212" y="12.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21723" stdDeviation=".5"/></filter><filter id="iKiFa3d" width="22.097" height="14.003" x="5.212" y="12.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.847059 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21723"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.94902 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21723" result="effect2_innerShadow_18_21723"/></filter><radialGradient id="i8XipIe" cx="0" cy="0" r="1" gradientTransform="rotate(138.122 13.9 7.015)scale(3.1289 2.97077)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="pkh-hm6gr"/><stop offset="1" class="cir_4gb8k"/></radialGradient><linearGradient id="i0DTb1b" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="tlc6-8sdm"/><stop offset="1" class="b38j-ob4y"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chart-increasing-with-yen" /></template>
<style>
.b38j-ob4y {
  stop-color: var(--svg-color--51c483, #51C483);
}

.cir_4gb8k {
  stop-color: var(--svg-color--7dffb1, #7DFFB1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.m_f__4-zd {
  fill: var(--svg-color--55c480, #55C480);
  fill-rule: evenodd;
  d: path("M26.79 13.385a.75.75 0 0 1 0 1.06L16.364 24.87a1.75 1.75 0 0 1-2.48-.005l-2.617-2.637a.25.25 0 0 0-.354 0l-4.422 4.421a.75.75 0 0 1-1.06-1.06l4.422-4.422a1.75 1.75 0 0 1 2.48.005l2.616 2.637a.25.25 0 0 0 .355 0l10.423-10.423a.75.75 0 0 1 1.061 0");
}

.mn0__lb4b {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  rx: 4px;
}

.pkh-hm6gr {
  stop-color: var(--svg-color--7dffb1, #7DFFB1);
}

.tlc6-8sdm {
  stop-color: var(--svg-color--54e58e, #54E58E);
}

.ukf8cjbkk {
  fill: var(--svg-color--f1e9ff, #F1E9FF);
  fill-rule: evenodd;
  d: path("M26.79 13.385a.75.75 0 0 1 0 1.06L16.364 24.87a1.75 1.75 0 0 1-2.48-.005l-2.617-2.637a.25.25 0 0 0-.354 0l-4.422 4.421a.75.75 0 0 1-1.06-1.06l4.422-4.422a1.75 1.75 0 0 1 2.48.005l2.616 2.637a.25.25 0 0 0 .355 0l10.423-10.423a.75.75 0 0 1 1.061 0");
}

.vhr_jbbnt {
  fill: var(--svg-color--f1e9ff, #F1E9FF);
  d: path("M6.475 5.43a.75.75 0 1 0-1.325.703l2.113 3.984a.2.2 0 0 1-.176.294H5.953a.75.75 0 1 0 0 1.5h1.62c.11 0 .2.09.2.2v.55a.2.2 0 0 1-.2.2h-1.62a.75.75 0 0 0 0 1.5h1.62c.11 0 .2.09.2.2v1.2a.75.75 0 0 0 1.5 0v-1.2c0-.11.09-.2.2-.2h1.93a.75.75 0 0 0 0-1.5h-1.93a.2.2 0 0 1-.2-.2v-.55c0-.11.09-.2.2-.2h1.93a.75.75 0 0 0 0-1.5H9.996a.2.2 0 0 1-.174-.298l2.234-3.963a.75.75 0 0 0-1.307-.737L8.632 9.169a.1.1 0 0 1-.175-.002z");
}

.ybktwea4p {
  fill: var(--svg-color--55c480, #55C480);
  d: path("M6.475 5.43a.75.75 0 1 0-1.325.703l2.113 3.984a.2.2 0 0 1-.176.294H5.953a.75.75 0 1 0 0 1.5h1.62c.11 0 .2.09.2.2v.55a.2.2 0 0 1-.2.2h-1.62a.75.75 0 0 0 0 1.5h1.62c.11 0 .2.09.2.2v1.2a.75.75 0 0 0 1.5 0v-1.2c0-.11.09-.2.2-.2h1.93a.75.75 0 0 0 0-1.5h-1.93a.2.2 0 0 1-.2-.2v-.55c0-.11.09-.2.2-.2h1.93a.75.75 0 0 0 0-1.5H9.996a.2.2 0 0 1-.174-.298l2.234-3.963a.75.75 0 0 0-1.307-.737L8.632 9.169a.1.1 0 0 1-.175-.002z");
}

</style>
