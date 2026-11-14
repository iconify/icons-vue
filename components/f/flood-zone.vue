<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k06n4nbgh"/><path class="mfo0vvp8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flood-zone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k06n4nbgh {
  d: path("M11.482 19.565L8.5 18.5l-6 2.5V5.5l6-2.5l7 2.5l6-2.5v10.067M8.5 3v15.5m7-13v7.4");
}

.mfo0vvp8a {
  d: path("M14.25 16.5q1.25-1.25 2.5 0t2.5 0t2.5 0m-7.5 3.5q1.25-1.25 2.5 0t2.5 0t2.5 0");
}

</style>
