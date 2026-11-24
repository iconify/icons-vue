<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kpldm1ado"/><path class="n5pryla1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-edit-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kpldm1ado {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 8v12l-5 1l1-5a8.945 8.945 0 0 1 16-8Zm5 13v-3l5-5l3 3l-5 5Z");
}

.n5pryla1x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 20l-5 1l1-5a8.944 8.944 0 1 1 16-8m-7 13v-3l5-5l3 3l-5 5Z");
}

</style>
