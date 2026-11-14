<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v_ui7pbkk"/><path class="yl2ybz-3i"/><path class="kd2fcg4ti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-bar-target" /></template>
<style>
.kd2fcg4ti {
  d: path("M2.75 8h5m1.75 2h5m1.75.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_ui7pbkk {
  d: path("M2.5 21h19");
}

.yl2ybz-3i {
  fill: currentColor;
  d: path("M4 21v-9h2.5v9Zm6.75 0V5h2.5v16Zm6.75 0v-6.5H20V21Z");
}

</style>
