<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9f-x9b6f"/><path class="aq2y4ynms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-view" /></template>
<style>
.aq2y4ynms {
  d: path("M6.5 11.5h3v8h-3Zm4.25 8v-11l1.5-2.5l1.5 2.5v11ZM15 9.5h2.5v10H15Z");
}

.l9f-x9b6f {
  d: path("M4 3h16v16.5H4ZM2.5 19.5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
