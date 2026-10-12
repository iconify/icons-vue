<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv-z7c9ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dress" /></template>
<style>
.kv-z7c9ry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 7.75l-.5-5m6 5l.5-5m-5.5 5h4.5q1 0 .82.98l-.39 2.04q-.18.98.27 1.87l3.85 7.72q.45.89-.55.89H5.75q-1 0-.55-.89l3.85-7.72q.45-.89.27-1.87l-.39-2.04q-.18-.98.82-.98M9.5 12h5");
}

</style>
