<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rhk44qbdt"/><path class="wtlt_w2cm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:license-compliance" /></template>
<style>
.rhk44qbdt {
  d: path("M12.8 20H2.5V4h19v8.3m0 6.9v.8h-.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtlt_w2cm {
  d: path("M6 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 8a3 3 0 0 1 6 0m3-8h4.5m-3.75 9l2 2L21 15.75");
}

</style>
