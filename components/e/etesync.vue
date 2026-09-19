<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx9jlb1fn"/><path class="p1geu4llt"/><path class="li_o47goo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:etesync" /></template>
<style>
.li_o47goo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.18v3.48l-4.78-4.79L24 10.09h0zm0 15.64v-3.47l4.78 4.78L24 37.91z");
}

.p1geu4llt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.67 29.18A9.26 9.26 0 0 0 24 14.75m-7.67 4.08A9.16 9.16 0 0 0 14.75 24A9.25 9.25 0 0 0 24 33.25");
}

.xx9jlb1fn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l-6 6H9.51V18l-6 6l6 6v8.48H18l6 6l6-6h8.48V30l6-6l-6-6V9.51H30Z");
}

</style>
