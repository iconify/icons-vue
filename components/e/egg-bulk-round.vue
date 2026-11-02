<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pa3oo7hnv"/><path class="j224_mbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:egg-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j224_mbwo {
  d: path("M15.685 15.557a4 4 0 0 1-.857 1.271A3.98 3.98 0 0 1 12 18a1 1 0 0 1 0-2c.533 0 1.039-.207 1.414-.586c.377-.377.588-.881.586-1.414a1 1 0 0 1 2 0a4 4 0 0 1-.315 1.557");
}

.pa3oo7hnv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2c1.162 0 2.236.46 3.162 1.139c1.008.74 1.825 1.711 2.494 2.762C19.163 8.269 20 11.196 20 14a8 8 0 0 1-16 0c0-2.804.837-5.731 2.344-8.099c.669-1.051 1.486-2.022 2.494-2.762C9.764 2.46 10.838 2 12 2");
}

</style>
