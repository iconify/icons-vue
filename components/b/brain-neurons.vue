<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsbjxdb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brain-neurons" /></template>
<style>
.hsbjxdb8q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.355 14.248q.862 2.464 3.34 2.959q3.44 2.482 7.495.762l1.659 2.903q.112.197.316.299q1.085.543 2.045.062q1.04-.519 1.04-1.733v-2.799q2.054-.277 3.146-2.133q1.154-1.961.386-4.12q.521-2.46-1.026-4.523q-1.535-2.046-3.949-2.167Q15.132 2.25 12.5 2.25q-2.589 0-4.252 1.459q-2.44-.253-4.201 1.621q-1.82 1.938-1.339 4.545q-1.144 2.114-.353 4.373M9.75 7.5q0-2.25 2.25-2.25t2.25 2.25q0 .47-.098.841l1.639 1.639q.489-.23 1.209-.23q2.25 0 2.25 2.25T17 14.25T14.75 12q0-.47.098-.841L13.209 9.52q-.489.23-1.209.23t-1.209-.23l-1.639 1.639q.098.371.098.841q0 2.25-2.25 2.25T4.75 12T7 9.75q.72 0 1.209.23l1.639-1.639Q9.75 7.97 9.75 7.5");
}

</style>
