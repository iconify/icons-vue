<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="medfw0i1r"/><path class="vmobszrlt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:container-build" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.medfw0i1r {
  d: path("M14.971 17.382L11 19.5l-7.5-4v-9l7.5-4l7.5 4V12");
}

.vmobszrlt {
  d: path("m3.5 6.5l7.5 4l7.5-4m-7.5 4v9m8.677-4.341l1.414 1.414a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0l-1.414-1.414a1.25 1.25 0 0 1 0-1.768a1.25 1.25 0 0 1 1.768 0M18.75 17.5L15 21.25");
}

</style>
