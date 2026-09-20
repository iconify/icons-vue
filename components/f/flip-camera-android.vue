<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w353mjemf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flip-camera-android" /></template>
<style>
.w353mjemf {
  fill: currentColor;
  d: path("M12 22q-3.575 0-6.325-2.25T2.2 14h2.05q.7 2.65 2.85 4.325T12 20q2.15 0 4-1.062T18.9 16H16v-2h6v6h-2v-2q-1.425 1.9-3.525 2.95T12 22m-2.125-7.875Q9 13.25 9 12t.875-2.125T12 9t2.125.875T15 12t-.875 2.125T12 15t-2.125-.875M2 10V4h2v2q1.425-1.9 3.525-2.95T12 2q3.575 0 6.325 2.25T21.8 10h-2.05q-.7-2.65-2.85-4.325T12 4Q9.85 4 8 5.063T5.1 8H8v2z");
}

</style>
