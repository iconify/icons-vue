<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rguehbm3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:headphones-over-ear" /></template>
<style>
.rguehbm3i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 13.254V11.5q0-3.417 2.416-5.834T12 3.25t5.834 2.416Q20.25 8.083 20.25 11.5v1.754q.289.188.548.448q.952.952.952 2.298v2q0 1.346-.952 2.298t-2.298.952q-3.25 0-3.25-3.25v-2q0-3.25 3.25-3.25q.127 0 .25.008V11.5q0-2.796-1.977-4.773T12 4.75T7.227 6.727T5.25 11.5v1.258q.123-.008.25-.008q3.25 0 3.25 3.25v2q0 3.25-3.25 3.25T2.25 18v-2q0-1.346.952-2.298q.259-.26.548-.448");
}

</style>
