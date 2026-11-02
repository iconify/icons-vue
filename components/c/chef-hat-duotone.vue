<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iaohjy_jn"/><path class="b231m2b9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-duotone" /></template>
<style>
.b231m2b9q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15c-4.622-1.734-2.894-8.645 2-8a4 4 0 1 1 8 0c4.894-.645 6.622 6.266 2 8v4a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2zm0 2h12");
}

.ft5dv1b6b {
  fill: none;
}

.iaohjy_jn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 7a4 4 0 0 1 8 0c4.895-.638 6.62 6.259 2 8v4a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-4c-4.62-1.741-2.895-8.638 2-8");
}

</style>
