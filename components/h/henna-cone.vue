<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv-8cjzax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:henna-cone" /></template>
<style>
.fv-8cjzax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.35 16.34l3.3-6.18q.35-.66.88-.13l2.44 2.44q.53.53-.13.88l-6.18 3.3q-.66.35-.31-.31m5.4-5.09L14 9m.2-.57l1.1-3.11q.2-.57.62-.15l1.91 1.91q.42.42-.15.62l-3.11 1.1q-.57.2-.37-.37M4.25 20c1.5-1 3 .25 4.5-.5s3 .5 4.5-.25");
}

</style>
