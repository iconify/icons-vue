<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qamqa3bal"/><path class="k9_zhfxec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k9_zhfxec {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-2 4h3a1 1 0 0 1 1 1v2c0 2.5-1.5 4-4 5c-2.5-1-4-2.5-4-5v-2a1 1 0 0 1 1-1z");
}

.qamqa3bal {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.034 3.034q-.01-.01-.022-.004a.02.02 0 0 0-.012.018V7c0 1.103.897 1.998 2 2h-4a2 2 0 0 0-2 2v10H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h6ZM14 13h6a1 1 0 0 1 1 1v2c-.002 2.649-1.701 4.08-4 5c-2.299-.92-3.998-2.351-4-5v-2a1 1 0 0 1 1-1");
}

</style>
