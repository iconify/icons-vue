<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ge7p804hb"/><path class="ejjew-f3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magazine-spread" /></template>
<style>
.ejjew-f3g {
  d: path("M16.25 8.5h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5m-1.5 7h4");
}

.ge7p804hb {
  d: path("M2.5 5H10l2 1.5L14 5h7.5v14H14l-2 1.5l-2-1.5H2.5ZM12 6.5v14m-6.75-11h4m-4 4h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
