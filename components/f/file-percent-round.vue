<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oestyssqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-percent-round" /></template>
<style>
.oestyssqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4m-5 4l-4 4m0-4h.01M14 17h.01");
}

</style>
