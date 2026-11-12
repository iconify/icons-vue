<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci1x_rbrb"/><path class="yvcxd9stk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-burndown-bulk-round" /></template>
<style>
.ci1x_rbrb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 16a3 3 0 0 0 3 3h14a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.yvcxd9stk {
  d: path("M11 6c.351 0 .677.184.857.486L14.566 11H16c1.348.001 2.357 1.478 2.894 2.553l3 6a1 1 0 1 1-1.788.894l-3-6c-.216-.431-.47-.857-.813-1.2c-.093-.093-.2-.197-.324-.247H14a1 1 0 0 1-.857-.486L10.434 8H7a1 1 0 0 1 0-2Z");
}

</style>
