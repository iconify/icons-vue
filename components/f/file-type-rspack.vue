<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGbUipIddK)" class="ycs44_jvl"/><path class="xv6sq0bql"/><path class="al117u1jl"/><path fill="url(#SVG21l1SdxX)" class="iwo-k9bpn"/><path class="ryr3gncnd"/><path class="c2cyxbbab"/><ellipse transform="rotate(4.81 -121.2 263.1)scale(-1 1)" class="s9c3yib4i"/><ellipse transform="rotate(-169.8 11.5 2.2)scale(1 -1)" class="mng3pob6d"/><path class="l86muabpb"/><defs><linearGradient id="SVGbUipIddK" x1="26.98" x2="18.99" y1="19.07" y2="27.07" gradientUnits="userSpaceOnUse"><stop offset=".01" class="gew2f_byd"/><stop offset=".57" class="gbucu3b5o"/></linearGradient><linearGradient id="SVG21l1SdxX" x1="23.02" x2="6.88" y1="4.94" y2="24.32" gradientUnits="userSpaceOnUse"><stop offset=".01" class="tm9rzo2jb"/><stop offset=".46" class="gbucu3b5o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-rspack" /></template>
<style>
.al117u1jl {
  fill: var(--svg-color--ff7043, #ff7043);
  d: path("M26.99 27.07a5.65 5.65 0 0 1-9.21-6.18a5.6 5.6 0 0 0 1.58 4.85a5.65 5.65 0 0 0 9.21-1.82A5.6 5.6 0 0 1 27 27.07");
}

.c2cyxbbab {
  fill: var(--svg-color--ff8a65, #ff8a65);
  d: path("M23.9 24.2a12 12 0 0 1-17 .2a12 12 0 0 1-2.6-13.1a12 12 0 0 0 3.3 10.2a12 12 0 0 0 17.1-.1a12 12 0 0 0 2.7-4a12 12 0 0 1-3.5 6.8");
}

.ft5dv1b6b {
  fill: none;
}

.gbucu3b5o {
  stop-color: var(--svg-color--ffab91, #ffab91);
}

.gew2f_byd {
  stop-color: var(--svg-color--ffb74d, #ffb74d);
}

.iwo-k9bpn {
  d: path("M6.9 24.3a11.5 11.5 0 0 1-2-14c.2-.4-1.2-1-1-2c.2-.7 1-1.3 1.2-1.6c5.4-4.6 15-4.6 19.7 0s3.5 13-1 17.6a12 12 0 0 1-17 0");
}

.l86muabpb {
  stroke: var(--svg-color--4e342e, #4e342e);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("M7.4 4.5C3 7 2.7 8.6 3.9 9.9c2 2 7.8.4 8.4 2.6c.4 1.3-.5 2.8.7 4.5c1.6 2.2 6.8.3 7 4.5");
}

.mng3pob6d {
  cx: 3.7px;
  cy: 2.4px;
  fill: var(--svg-color--fafafa, #fafafa);
  rx: 3.7px;
  ry: 2.4px;
}

.ryr3gncnd {
  fill: var(--svg-color--4e342e, #4e342e);
  d: path("M15.22 2c3.9 0 7.84 1.23 10.46 3.86c2.64 2.64 3.61 6.27 3.32 9.79a15.6 15.6 0 0 1-4.4 9.57a13.17 13.17 0 0 1-18.62 0C2.29 21.54.76 15.61 3.43 10.37C3.1 10 2.4 9.16 2.7 8a3.4 3.4 0 0 1 .8-1.5c.27-.3.7-.7.73-.72l.03-.03l.04-.04C7.25 3.21 11.31 2 15.22 2m9.57 4.76c-4.65-4.65-14.32-4.63-19.65-.08l-.3.28c-.35.33-.8.8-.9 1.36c-.26 1 1.2 1.62.95 2.02l-.25.45C2.15 15.52 3.5 20.94 6.88 24.32a11.9 11.9 0 0 0 16.38.43l.45-.43c4.5-4.5 5.65-12.4 1.5-17.11z");
}

.s9c3yib4i {
  cx: 1.97px;
  cy: 1.43px;
  fill: var(--svg-color--fafafa, #fafafa);
  rx: 1.97px;
  ry: 1.43px;
}

.tm9rzo2jb {
  stop-color: var(--svg-color--ffe082, #ffe082);
}

.xv6sq0bql {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M18.09 18.17a6.93 6.93 0 1 1 9.8 9.8a6.93 6.93 0 0 1-9.8-9.8m8.9.9a5.65 5.65 0 0 0-8 0l-.2.22a5.65 5.65 0 1 0 8.4 0z");
}

.ycs44_jvl {
  d: path("M18.99 27.07a5.65 5.65 0 1 1 8-8a5.65 5.65 0 0 1-8 8");
}

</style>
