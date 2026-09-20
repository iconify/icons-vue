<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7k41sc7j"/><path class="w6xpgbs7z"/><path class="jbn80zanz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:converter" /></template>
<style>
.jbn80zanz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.14 7.236za3.62 3.62 0 0 1 5.12 0l1.787 1.789l-5.119 5.119l-1.788-1.789a3.62 3.62 0 0 1 0-5.119m22.954 24.071l-6.195-2.192l5.12-5.12l2.192 6.195a.875.875 0 0 1-1.117 1.117");
}

.p7k41sc7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v37h37z");
}

.w6xpgbs7z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.62 36.38V20.275L27.724 36.38zM5.5 15.967h1.737M5.5 22.273h1.737M5.5 28.579h1.737M5.5 34.886h1.737m24.796 5.877V42.5m-6.306-1.737V42.5m-6.306-1.737V42.5m-6.307-1.737V42.5m6.814-28.357l5.119-5.119l14.971 14.972l-5.119 5.118z");
}

</style>
