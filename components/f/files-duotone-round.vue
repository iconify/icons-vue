<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="khuiqacrc"/><path class="a76rvbb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-duotone-round" /></template>
<style>
.a76rvbb1i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6H7a4 4 0 0 0-4 4v7a4 4 0 0 0 4 4h2a4 4 0 0 0 4-4v-6M8 6l5 5M8 6v4a1 1 0 0 0 1 1h4m-2-8h5m0 0l5 5m-5-5v4a1 1 0 0 0 1 1h4m0 0v6a4 4 0 0 1-4 4");
}

.ft5dv1b6b {
  fill: none;
}

.khuiqacrc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 10.293A1 1 0 0 1 14 11v6a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-7a5 5 0 0 1 5-5h1c.265 0 .52.105.707.293ZM8 10a1 1 0 0 0 1 1h3L8 7Z");
}

</style>
