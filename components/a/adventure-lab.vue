<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lyy48fmnf"/><path class="wzh1_nbge"/><path class="c1qqw1byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adventure-lab" /></template>
<style>
.c1qqw1byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.105 27.055c-3.408-2.434-5.842-4.868-14.605-4.868m.974 18.5c2.92 1.136 9.834 1.363 14.118-2.921c5.355-5.356 13.37.629 15.092.973c7.303 1.46 10.224-6.815-4.868-11.684");
}

.lyy48fmnf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.79 12.45a1.947 1.947 0 1 1-3.895 0a1.947 1.947 0 0 1 3.895 0");
}

.wzh1_nbge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.684 12.45c0 2.353-3.107 6.452-4.79 8.5a1.352 1.352 0 0 1-2.105 0c-1.682-2.048-4.79-6.147-4.79-8.5a5.842 5.842 0 0 1 11.685 0M5.5 36.792c6.004-6.329 23.368-17.515 37-7.388");
}

</style>
