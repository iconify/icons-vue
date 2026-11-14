<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2uwfltgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:funnel-middle" /></template>
<style>
.g2uwfltgz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.75h14q1.236 0 1.789 1.106q.553 1.105-.189 2.094l-1.05 1.4q-.675.9-1.8.9H6.25q-1.125 0-1.8-.9L3.4 5.95q-.742-.989-.189-2.094Q3.764 2.75 5 2.75m9.175 6.75h-4.35q-1.185 0-1.72 1.057q-.536 1.057.165 2.012l.926 1.262q.674.919 1.814.919h1.98q1.14 0 1.814-.919l.926-1.262q.701-.955.165-2.012T14.175 9.5M11.75 16h.5q2.25 0 2.25 2.25v1.5q0 2.25-2.25 2.25h-.5Q9.5 22 9.5 19.75v-1.5Q9.5 16 11.75 16");
}

</style>
