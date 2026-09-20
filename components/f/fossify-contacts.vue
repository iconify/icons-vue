<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-os5ecbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fossify-contacts" /></template>
<style>
.n-os5ecbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.717 42.38c2.232 0 5.076-.387 4.759-6.743c-.31-6.22-10.38-9.372-18.476-9.372S5.834 29.418 5.524 35.637c-.317 6.356 2.527 6.743 4.76 6.743zm-4.416-27.46a9.301 9.301 0 1 1-18.602 0a9.301 9.301 0 1 1 18.602 0");
}

</style>
