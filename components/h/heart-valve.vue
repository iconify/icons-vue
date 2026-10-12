<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6wymvb-p"/><path class="jj2tur7pb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heart-valve" /></template>
<style>
.h6wymvb-p {
  d: path("M12 2.75a9.25 9.25 0 1 1 0 18.5a9.25 9.25 0 1 1 0-18.5m0 2.5a6.75 6.75 0 1 0 0 13.5a6.75 6.75 0 1 0 0-13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj2tur7pb {
  d: path("m11.18 10.02l-1.37-.64q-.82-.39-.01-.79l1.39-.69q.81-.4 1.62 0l1.39.69q.81.4-.01.79l-1.37.64q-.82.38-1.64 0m2.94 2.26l1.25-.86q.74-.52.68.38l-.1 1.55q-.05.9-.8 1.4l-1.3.86q-.75.5-.67-.4l.13-1.51q.08-.9.81-1.42m-3.43 1.42l.13 1.51q.08.9-.67.4l-1.3-.86q-.75-.5-.8-1.4l-.1-1.55q-.06-.9.68-.38l1.25.86q.73.52.81 1.42");
}

</style>
