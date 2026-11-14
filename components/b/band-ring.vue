<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7z38b88y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:band-ring" /></template>
<style>
.d7z38b88y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 10.25q-.001-2.605 3.007-4.36Q8.068 4.248 12 4.248t6.743 1.641q3.009 1.755 3.007 4.361v3.25q-.002 2.605-3.009 4.359Q15.93 19.498 12 19.498t-6.741-1.639Q2.252 16.105 2.25 13.5zm3 0Q5.25 7.5 12 7.5t6.75 2.75T12 13t-6.75-2.75m-1.5 3.257q.006 1.739 2.265 3.056Q8.476 17.998 12 17.998t5.985-1.435q2.259-1.317 2.265-3.056q-.624.589-1.507 1.104q-2.811 1.641-6.743 1.641t-6.743-1.641q-.883-.515-1.507-1.104");
}

</style>
