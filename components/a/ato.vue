<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tvorfib1k"/><path class="eqjc64b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ato" /></template>
<style>
.eqjc64b_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 30zc-2.1 0-3.8-1.7-3.8-3.8v-2.5c0-2.1 1.7-3.8 3.8-3.8s3.8 1.7 3.8 3.8v2.5c0 2.1-1.7 3.8-3.8 3.8");
}

.tvorfib1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 12.8C9.4 6.4 16.4 2.4 24 2.4c11.8 0 21.5 9.7 21.5 21.5c0 3.2-.7 6.3-2.1 9.2M2.5 24.7v-.8c0-3.2.7-6.3 2-9.2m2.7 22.7C6 35.9 5 34.3 4.3 32.5C3.5 30.8 3 28.9 2.7 27m16 17.8c-1.9-.5-3.7-1.2-5.5-2.2S10 40.4 8.6 39m24.2 4.6c-2.8 1.2-5.7 1.9-8.8 1.9c-1 0-2-.1-3-.2m21.6-10.1c-1 1.6-2.1 3-3.4 4.3s-2.8 2.4-4.4 3.3M18.4 26.2c0 2.1-1.7 3.8-3.8 3.8s-3.8-1.7-3.8-3.8v-2.5c0-2.1 1.7-3.8 3.8-3.8s3.8 1.7 3.8 3.8m0 6.3V19.9m5.5-3.3V30m-2.1-10.1h4");
}

</style>
