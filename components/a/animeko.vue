<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zbv7hoa4b"/><path class="s3ezkibdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:animeko" /></template>
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

.s3ezkibdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.876 16.928c4.602.657 10.1.12 15.36-.598m-2.451 3.945c-1.096 6.604-10.14 15.04-12.91 11.176c-1.976-2.76 2.3-9.943 10.4-10.04c4.96-.06 7.112 2.748 7.112 6.095s-2.63 4.9-6.335 5.977");
}

.zbv7hoa4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.63 14.12c-1.435 6.095-1.076 12.31.358 18.227");
}

</style>
