<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lg6o94b4d"/><path class="ctnnjtb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adblock-plus-fur-samsung-internet" /></template>
<style>
.ctnnjtb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.663 5.5H16.337L5.5 16.337v15.326L16.337 42.5h15.326L42.5 31.663V16.337z");
}

.lg6o94b4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.532 30.015V17.988h3.909a4.059 4.059 0 0 1 0 8.118h-3.909m-5.557-2.107a3.007 3.007 0 0 1 0 6.013h-4.96V17.985h4.96a3.007 3.007 0 1 1 0 6.014m0 0h-4.961m-2.546 6.016l-3.909-12.027L9.5 30.015m1.353-4.059h5.262");
}

</style>
