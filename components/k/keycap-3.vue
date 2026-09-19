<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAfQp2M)"><rect fill="url(#iU0Jrhc)" class="d1z2h9b3r"/><rect fill="url(#i1p5Utc)" class="d1z2h9b3r"/></g><g filter="url(#iOgsbBe)"><path stroke="url(#icMKBWk)" class="nrnhuqtnn"/></g><g filter="url(#ig2Vprq)"><path stroke="url(#iIW2Dae)" class="bkzv52mly"/></g><g filter="url(#i68ywqc)"><path class="qpcnaqbkk"/></g><g filter="url(#iVq1m5b)"><path class="javfr4b8g"/></g><defs><filter id="iAfQp2M" width="28.875" height="28.875" x="2.289" y=".563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3300" result="effect2_innerShadow_18590_3300"/></filter><filter id="iOgsbBe" width="5.5" height="28.375" x="25.727" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3300" stdDeviation="1"/></filter><filter id="ig2Vprq" width="27.281" height="5.5" x="3.003" y=".625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3300" stdDeviation="1"/></filter><filter id="i68ywqc" width="11.957" height="18.5" x="10.245" y="6.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3300" stdDeviation=".5"/></filter><filter id="iVq1m5b" width="11.357" height="17.9" x="10.245" y="6.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3300"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3300" result="effect2_innerShadow_18590_3300"/></filter><linearGradient id="iU0Jrhc" x1="16.227" x2="16.227" y1="5.137" y2="38.39" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="icMKBWk" x1="28.977" x2="28.977" y1="4.063" y2="26.938" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iIW2Dae" x1="28.691" x2="3.159" y1="3.625" y2="3.625" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="i1p5Utc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.946 3.656)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keycap-3" /></template>
<style>
.bkzv52mly {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.753 3.375h21.781");
}

.d1z2h9b3r {
  width: 27.875px;
  height: 27.875px;
  x: 2.289px;
  y: 1.563px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.javfr4b8g {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M14.743 11.632a1.556 1.556 0 1 1 2.03 2.099a.1.1 0 0 1-.03.008a1.75 1.75 0 0 0-.237 3.441l.086.023a1.558 1.558 0 0 1-.446 3.047a1.56 1.56 0 0 1-1.483-1.083a1.75 1.75 0 0 0-3.335 1.061a5.057 5.057 0 1 0 8.788-4.664a.1.1 0 0 1 0-.128a5.056 5.056 0 1 0-8.526-5.324a1.75 1.75 0 0 0 3.153 1.52");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.nrnhuqtnn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.477 4.063v22.875");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.qpcnaqbkk {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M14.743 11.632a1.556 1.556 0 1 1 2.03 2.099a.1.1 0 0 1-.03.008a1.75 1.75 0 0 0-.237 3.441l.086.023a1.558 1.558 0 0 1-.446 3.047a1.56 1.56 0 0 1-1.483-1.083a1.75 1.75 0 0 0-3.335 1.061a5.057 5.057 0 1 0 8.788-4.664a.1.1 0 0 1 0-.128a5.056 5.056 0 1 0-8.526-5.324a1.75 1.75 0 0 0 3.153 1.52");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
