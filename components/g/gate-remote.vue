<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wkxm9vnjj"/><path class="p8r2yeb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gate-remote" /></template>
<style>
.p8r2yeb8f {
  d: path("M6.75 13.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6.358-12.197a3.5 3.5 0 0 1 2.839 2.839m-2.318-5.793a6.5 6.5 0 0 1 5.272 5.272");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wkxm9vnjj {
  d: path("M3.5 9h9v12.5h-9Z");
}

</style>
