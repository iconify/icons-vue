<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ta_khf4lj"/><path class="sanet-btk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:battery-charging-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sanet-btk {
  d: path("M200 56H32A24 24 0 0 0 8 80v96a24 24 0 0 0 24 24h168a24 24 0 0 0 24-24V80a24 24 0 0 0-24-24m8 120a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V80a8 8 0 0 1 8-8h168a8 8 0 0 1 8 8Zm48-80v64a8 8 0 0 1-16 0V96a8 8 0 0 1 16 0m-117.19 27.79a8 8 0 0 1 .35 7.79l-16 32a8 8 0 0 1-14.32-7.16L119.06 136H100a8 8 0 0 1-7.16-11.58l16-32a8 8 0 1 1 14.32 7.16L112.94 120H132a8 8 0 0 1 6.81 3.79");
}

.ta_khf4lj {
  d: path("M216 80v96a16 16 0 0 1-16 16H32a16 16 0 0 1-16-16V80a16 16 0 0 1 16-16h168a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
