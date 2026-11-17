<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e8stzhbzm"/><path class="joexu5j7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal-duotone-sharp" /></template>
<style>
.e8stzhbzm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 3v5H4V3ZM4 15V9h16v6Zm12 6H4v-5h12Z");
}

.ft5dv1b6b {
  fill: none;
}

.joexu5j7a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h9v6h7v6h-4v6H4zm0 6h9m-9 6h12");
}

</style>
