<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r05pbczar"/><path class="h_nwhmbey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-version" /></template>
<style>
.h_nwhmbey {
  d: path("M15.75 3.75v3a2 2 0 0 0 2 2h3M5.25 6v13M2.75 8.25v8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r05pbczar {
  d: path("M15.75 3.75h-5a2.5 2.5 0 0 0-2.5 2.5v12.5a2.5 2.5 0 0 0 2.5 2.5h7.5a2.5 2.5 0 0 0 2.5-2.5v-10Z");
}

</style>
