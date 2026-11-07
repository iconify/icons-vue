<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x2bqnmk0w"/><path class="k5xdbzbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k5xdbzbio {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 2l9 4.444v11.112L12 22l-9-4.444V6.444zM3 6.444l9 4.445l9-4.445m-9 4.445V22M7.5 4.222l9 4.445");
}

.x2bqnmk0w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21.443 5.548a1 1 0 0 1 .557.896v11.112a1 1 0 0 1-.557.896l-9 4.445a1 1 0 0 1-.886 0l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l9-4.445c.279-.137.607-.137.886 0Z");
}

</style>
