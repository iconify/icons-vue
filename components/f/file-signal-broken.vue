<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0cmz0boh"/><path class="t4qaumccy"/><path class="pal5-l9wu"/><path class="ty2x0tbhn"/><circle class="mqyo1zlrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-signal-broken" /></template>
<style>
.e0cmz0boh {
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqyo1zlrk {
  cx: 6.724px;
  cy: 15.234px;
  r: 1.055px;
}

.pal5-l9wu {
  stroke-linejoin: round;
  d: path("M10.4919 11.541C11.4247 12.4925 11.9998 13.7959 11.9998 15.2337C11.9998 16.6885 11.4109 18.0057 10.4585 18.9601");
}

.t4qaumccy {
  stroke-linejoin: round;
  d: path("M2 10V14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18M22 14V13.5629C22 11.8083 22 10.931 21.654 10.1541C21.308 9.3772 20.6559 8.79032 19.3517 7.61654L15.3929 4.05365C14.2651 3.03857 13.7012 2.53104 13.0092 2.26552C12.3173 2 11.5548 2 10.0298 2C6.23869 2 4.34315 2 3.17157 3.17157C2.51839 3.82475 2.22937 4.69989 2.10149 6");
}

.ty2x0tbhn {
  stroke-linejoin: round;
  d: path("M8.98487 13.1455C9.54455 13.6808 9.88965 14.4141 9.88965 15.223C9.88965 16.0415 9.5363 16.7826 8.96484 17.3195");
}

</style>
