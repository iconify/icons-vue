<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q74dr2dkj"/><path class="kmeyaxzmt"/><path class="zm8vp8ntx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1-gb-gift-bank" /></template>
<style>
.kmeyaxzmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.971 8.4c4.308 0 7.8 6.984 7.8 15.6s-3.492 15.6-7.8 15.6m-7.871 0c-4.308 0-7.8-6.984-7.8-15.6s3.492-15.6 7.8-15.6m7.8 0v31.2M20.1 24H4.5m39 0H27.9");
}

.q74dr2dkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 39.6c-8.616 0-15.6-6.984-15.6-15.6S11.484 8.4 20.1 8.4h7.8c8.616 0 15.6 6.984 15.6 15.6s-6.984 15.6-15.6 15.6z");
}

.zm8vp8ntx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.587 16.2H20.1v23.4m0-7.8H6.587m34.826-15.6H27.9m13.513 15.6H27.9");
}

</style>
