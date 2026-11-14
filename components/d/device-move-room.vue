<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q_a3l74xm"/><path class="hqntv7b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:device-move-room" /></template>
<style>
.hqntv7b-g {
  d: path("m9.5 3l2 2l-2 2M15 21v-3.5h3.5V21");
}

.q_a3l74xm {
  d: path("M2.5 14.5H9V21H2.5Zm9.5-3L16.75 7l4.75 4.5V21H12Zm-6.25.25V5h5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
