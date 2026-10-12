<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k11p5sbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iceberg" /></template>
<style>
.k11p5sbyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.58 3.25l2.09 3.25q.33.5.84.81l.23.13q.51.31.8.83l.67 1.21q.29.52.7.96l3.18 3.37q.41.44.2 1l-1.83 4.88q-.21.56-.8.65l-5.57.82q-.59.09-1.11-.22l-4.46-2.63Q5 18 4.93 17.4l-.36-3.3q-.07-.6.3-1.07l2.01-2.56q.37-.47.64-1.01l.71-1.42q.27-.54.48-1.1l1.33-3.63q.21-.56.54-.06m-7.83 8.5h18.5");
}

</style>
