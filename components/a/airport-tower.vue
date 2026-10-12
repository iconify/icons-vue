<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqaq5vb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-tower" /></template>
<style>
.kqaq5vb3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25v-2.5m-2 0h4m-7.25 2.5h10.5q1 0 .63.93l-1.26 3.14q-.37.93-1.37.93h-6.5q-1 0-1.37-.93L6.12 6.18q-.37-.93.63-.93m3 1.5l.5 2m1.75-2v2m2.25-2l-.5 2M11 10.25h2q.75 0 .82.75l.86 9.5q.07.75-.68.75h-4q-.75 0-.68-.75l.86-9.5q.07-.75.82-.75");
}

</style>
