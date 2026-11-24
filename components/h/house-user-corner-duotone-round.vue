<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xih8zubbn"/><path class="jf_812bxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jf_812bxo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21a4 4 0 0 1-4-4v-5.185a4 4 0 0 1 1.366-3.01l4-3.5a4 4 0 0 1 5.268 0L17.714 8M15 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-1 7c0-1.105 1.343-2 3-2s3 .895 3 2");
}

.xih8zubbn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.714 8H12a4 4 0 0 0-4 4v9a4 4 0 0 1-4-4v-5.185a4 4 0 0 1 1.366-3.01l4-3.5a4 4 0 0 1 5.268 0Z");
}

</style>
