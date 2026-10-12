<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nrb0bcc"/><path class="vzq052bxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:helicopter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nrb0bcc {
  d: path("M11.75 8.75h2.5a6 6 0 0 1 6 6V15a2 2 0 0 1-2 2h-6.5a4 4 0 0 1-4-4v-.25a4 4 0 0 1 4-4");
}

.vzq052bxi {
  d: path("M14.75 8.75v4.5H20m-12.25-.5h-4.5m0-2.25V15m5.5 5h11m-8.25-3v3m5.5-3v3M5.5 4.75h13m-6 0v4");
}

</style>
