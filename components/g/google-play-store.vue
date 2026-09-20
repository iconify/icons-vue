<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jr1eh5o8x"/><path class="ufnd6wkqk"/><path class="u1ml5lb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-play-store" /></template>
<style>
.jr1eh5o8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.027 24.052L8.765 39.885C9.285 41.65 10.945 43 12.918 43q1.245 0 2.18-.623l18.17-10.279z");
}

.u1ml5lb5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.027 24.052l8.137-8.254L15.202 5.623C14.58 5.208 13.75 5 12.918 5C10.945 5 9.18 6.35 8.765 8.115z");
}

.ufnd6wkqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.95 20.262zl-7.786-4.464l-8.137 8.254l8.24 8.046l7.788-4.36c1.35-.727 2.284-2.18 2.284-3.738c-.104-1.558-1.038-3.011-2.388-3.738ZM8.765 8.115c-.104.311-.104.727-.104 1.142v29.59c0 .415 0 .727.104 1.142l16.262-15.937z");
}

</style>
