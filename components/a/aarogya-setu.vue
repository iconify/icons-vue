<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wiei2c4qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aarogya-setu" /></template>
<style>
.wiei2c4qs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.187 27.686C32.695 33.671 24 41.703 24 41.703s-3.505-3.238-7.47-7.134m-3.197-3.193c-3.345-3.402-6.446-6.787-7.515-8.638c-2.684-4.648-1.23-11.945 4.011-14.97S21.775 6.536 24 11.777c2.226-5.241 8.929-7.037 14.17-4.01s6.696 10.322 4.012 14.97a14 14 0 0 1-1.013 1.47");
}

</style>
