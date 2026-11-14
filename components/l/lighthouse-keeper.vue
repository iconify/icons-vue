<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="thgv6244e"/><path class="fm4s4cc7u"/><path class="z7n1jebfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lighthouse-keeper" /></template>
<style>
.fm4s4cc7u {
  d: path("M7.5 5h1A1.5 1.5 0 0 1 10 6.5v2A1.5 1.5 0 0 1 8.5 10h-1A1.5 1.5 0 0 1 6 8.5v-2A1.5 1.5 0 0 1 7.5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.thgv6244e {
  d: path("m4.763 19.774l1.293-8.5A1.5 1.5 0 0 1 7.539 10h.922a1.5 1.5 0 0 1 1.483 1.274l1.293 8.5A1.5 1.5 0 0 1 9.754 21.5H6.246a1.5 1.5 0 0 1-1.483-1.726M3.5 10h9");
}

.z7n1jebfb {
  d: path("m6.75 3.75l.189-.189a1.5 1.5 0 0 1 2.122 0l.189.189A.732.732 0 0 1 8.732 5H7.268a.732.732 0 0 1-.518-1.25m7.75 17.5c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5m1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
