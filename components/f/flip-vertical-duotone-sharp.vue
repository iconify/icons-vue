<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gxe5ulj0i"/><path class="im8-libzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gxe5ulj0i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 2h10a1.002 1.002 0 0 1 .707 1.707l-5 5a1 1 0 0 1-1.414 0l-5-5A1 1 0 0 1 7 2m4.293 13.293a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 17 22H7a1.002 1.002 0 0 1-.707-1.707Z");
}

.im8-libzf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 3l5 5l5-5zm-2 9h2m4 0h2m4 0h2M7 21l5-5l5 5z");
}

</style>
