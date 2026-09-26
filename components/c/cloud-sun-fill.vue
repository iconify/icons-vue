<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="eh9efdkoj"/><path class="nsj4trb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sun-fill" /></template>
<style>
.eh9efdkoj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 23C7.7909 23 6 21.2091 6 19C6 17.1481 7.2712 15.5383 9.0727 15.109C9.509 12.4509 11.8063 10.5 14.5 10.5C17.1937 10.5 19.491 12.4509 19.9273 15.109C21.7288 15.5383 23 17.1481 23 19C23 21.2091 21.2091 23 19 23L10 23Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsj4trb5y {
  d: path("M7.6787 10.9281C7.5606 10.6329 7.5 10.3179 7.5 10C7.5 8.6193 8.6193 7.5 10 7.5C10.5583 7.5 11.1004 7.6868 11.5402 8.0308M3.5 10L2 10M5.4038 5.4038L4.3431 4.3431M10 3.5L10 2M14.5962 5.4038L15.6569 4.3431");
}

</style>
