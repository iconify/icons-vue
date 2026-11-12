<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uama0jbpo"/><path class="ijwbgek4s"/><path class="jie9kjmui"/><path class="w1fn0ab-e"/><path class="vsegm02fm"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-scan-linear" /></template>
<style>
.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.ijwbgek4s {
  d: path("M22 15C22 18.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jie9kjmui {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 5.22876 22 9");
}

.uama0jbpo {
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 18.7712 2 15");
}

.vsegm02fm {
  d: path("M12 7C9.07268 7 7.08037 8.56222 5.89242 9.94021C5.29747 10.6303 5 10.9754 5 12C5 13.0246 5.29748 13.3697 5.89243 14.0598C7.08038 15.4378 9.07268 17 12 17C14.9273 17 16.9196 15.4378 18.1076 14.0598C18.7025 13.3697 19 13.0246 19 12C19 10.9754 18.7025 10.6303 18.1076 9.94021C16.9196 8.56222 14.9273 7 12 7Z");
}

.w1fn0ab-e {
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 5.22876 2 9");
}

</style>
