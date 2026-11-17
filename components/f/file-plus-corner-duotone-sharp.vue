<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="esus3r06j"/><path class="f1vw8acnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-plus-corner-duotone-sharp" /></template>
<style>
.esus3r06j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h8l.034.034q-.01-.01-.022-.004a.02.02 0 0 0-.012.018V8.98q.002.018.02.02H9v12H5Z");
}

.f1vw8acnu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-6 8h8m-4-4v8");
}

.ft5dv1b6b {
  fill: none;
}

</style>
