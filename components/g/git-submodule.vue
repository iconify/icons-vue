<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xuuapd7wd"/><path class="gvfe0uygz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-submodule" /></template>
<style>
.gvfe0uygz {
  d: path("M6 6.25V5a2 2 0 0 1 2-2h3.5l2 2h6a2 2 0 0 1 2 2v10m-13-1.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-3.25 0H8.5m3.5 0h3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xuuapd7wd {
  d: path("M2.5 11a2 2 0 0 1 2-2H8l2 2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H4.5a2 2 0 0 1-2-2Z");
}

</style>
