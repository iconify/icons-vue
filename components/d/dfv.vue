<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dk6cy58vn"/><path class="fcu595b_n"/><rect transform="rotate(45 24 24)" class="gusbizbab"/><path class="gmop51akl"/><path class="exfakmbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dfv" /></template>
<style>
.dk6cy58vn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.35 33.745c.76-6.075 5.52-11.65 5.52-11.65a18 18 0 0 0-2.395.701s1.549-5.316 5.93-6.806c-1.694-.73-2.249-.963-2.249-.963A25 25 0 0 1 25.75 13.8a3.28 3.28 0 0 1 3.16 1.853c3.383.104 6.771 1.652 4.931 5.508c-.76-1.753-2.57-2.016-5.024-1.694");
}

.exfakmbto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.948 16.264s-.137.82-.89.756c-.687-.058-.673-.96-.673-.96");
}

.fcu595b_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.722 34.674c-1.35-4.083-5.12-7.613-7.168-7.613c-2.156 0-1.606 3.213-1.606 3.213c-.73-3.243-1.187-6.639.555-8.325c1.81-1.753 3.71-1.548 6.136-1.18");
}

.gmop51akl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.078c1.809-.058 2.744-.03 3.766.526");
}

.gusbizbab {
  width: 31.671px;
  height: 31.671px;
  x: 8.164px;
  y: 8.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.575px;
}

</style>
