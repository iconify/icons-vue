<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jahhv7bmc"/><path class="t0qijpgme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jahhv7bmc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.t0qijpgme {
  d: path("M17 2a5 5 0 0 1 5 5v10a1 1 0 0 1-2 0V7a3 3 0 0 0-3-3H7a1 1 0 0 1 0-2Z");
}

</style>
