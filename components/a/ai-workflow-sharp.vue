<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n78r7jbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-workflow-sharp" /></template>
<style>
.n78r7jbeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h6.5v6.5h-6.5zm0 12h6.5v6.5h-6.5zM9.25 6H13v12H9.25M13 12h.75m3.75-3.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Z");
}

</style>
