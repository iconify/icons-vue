<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y-kz4tb1i"/><path class="kprumth-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flask-heart" /></template>
<style>
.kprumth-a {
  d: path("M12 18.25C9 16 9.25 13 10.75 13c.75 0 1.25.75 1.25 1.25c0-.5.5-1.25 1.25-1.25c1.5 0 1.75 3-1.25 5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-kz4tb1i {
  d: path("M9.5 2.5v6l-5.75 11Q3 21 4.75 21h14.5q1.75 0 1-1.5l-5.75-11v-6M8 2.5h8");
}

</style>
