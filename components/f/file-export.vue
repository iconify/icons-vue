<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wow50houi"/><path class="fouvjmbie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-export" /></template>
<style>
.fouvjmbie {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-8 6.25h10m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wow50houi {
  d: path("M19.25 11.25v-3l-5.5-5.5h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5v-1");
}

</style>
