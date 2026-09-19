<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="nh6-rvbpx"/><path class="x5fy562wu"/><path class="qq1e7-bje"/><path class="pd-hifczi"/><path class="d0-r9rbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:familysearch-memories" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d0-r9rbyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.735 28.21s-.462 1.517-1.914 2.177m-3.497-5.015s.264 1.254 1.782 2.31");
}

.nh6-rvbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.372 10.952a.02.02 0 0 0-.017.017v2.464h21.273q.016.001.017.016v21.118h2.56q.014-.001.016-.016V10.969a.02.02 0 0 0-.017-.017z");
}

.pd-hifczi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.02 23.129c-2.442 7.918 2.507 11.415 2.507 11.415h-2.244s-4.42-4.355-.264-11.415");
}

.qq1e7-bje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.817 21.743h3.629v3.629h-3.629zm9.633-2.177h3.365v3.365H25.45zm-4.421.66h2.837v2.837h-2.837zm1.914 4.42h3.563v3.563h-3.563zm5.147-.066h1.518v1.518H28.09zm-10.426-6.268h1.913v1.913h-1.913zm3.365-2.375h2.837v2.837h-2.837z");
}

.x5fy562wu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.645 34.567l-.003-21.126l-21.287-.008h-2.56a.02.02 0 0 0-.016.016v23.582q.002.016.017.017h23.832q.016-.002.017-.017z");
}

</style>
