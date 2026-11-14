<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gatw2fb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dive-regulator" /></template>
<style>
.gatw2fb1t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.373 4.373Q2.25 6.497 2.25 9.5t2.123 5.127T9.5 16.75q2.982 0 5.097-2.094q1.013.514 2.399.931q.995.299 1.332.931Q16 16.72 16 19.25Q16 22 18.75 22h1q2.75 0 2.75-2.75q0-2.661-2.575-2.747q-.363-1.711-2.497-2.353q-1.05-.316-1.844-.682Q16.75 11.725 16.75 9.5q0-3.003-2.123-5.127T9.5 2.25T4.373 4.373M6.25 9.5q0-3.25 3.25-3.25t3.25 3.25t-3.25 3.25T6.25 9.5");
}

</style>
