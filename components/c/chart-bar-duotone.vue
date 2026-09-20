<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="kjnb-_bga"/><path class="i1_xx0bwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-bar-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i1_xx0bwc {
  d: path("M224 200h-8V40a8 8 0 0 0-8-8h-56a8 8 0 0 0-8 8v40H96a8 8 0 0 0-8 8v40H48a8 8 0 0 0-8 8v64h-8a8 8 0 0 0 0 16h192a8 8 0 0 0 0-16M160 48h40v152h-40Zm-56 48h40v104h-40Zm-48 48h32v56H56Z");
}

.kjnb-_bga {
  d: path("M208 40v168h-56V40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
