<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0l_lpgnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boiled-egg" /></template>
<style>
.l0l_lpgnu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.399 5.936Q15.258 2.25 12 2.25T6.601 5.936Q4.75 9.124 4.75 13q0 3.331 2.02 5.733Q8.887 21.25 12 21.25t5.23-2.517q2.02-2.402 2.02-5.733q0-3.876-1.851-7.064M8.25 13.5q0-3.75 3.75-3.75t3.75 3.75T12 17.25T8.25 13.5");
}

</style>
