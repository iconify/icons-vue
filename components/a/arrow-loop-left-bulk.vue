<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mbl6b1m9l"/><path class="f-2hmyfdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-loop-left-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f-2hmyfdg {
  d: path("M12 19H7.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L7.414 17H12a6 6 0 0 0 5.881-4.811a5.998 5.998 0 0 0-9.199-6.188A6 6 0 0 0 6 11a1 1 0 0 1-2 0a8 8 0 1 1 8 8");
}

.mbl6b1m9l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 11a7 7 0 1 1 7 7H5Z");
}

</style>
