<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bzonbq2mj"/><path class="hfatccbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-bulk-round" /></template>
<style>
.bzonbq2mj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 6h8a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-6a5 5 0 0 1 5-5");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hfatccbwj {
  d: path("M12 2c1.657.001 3 1.343 2.999 3v2a1 1 0 0 1-2 0V4.998A1 1 0 0 0 11 5v2a1 1 0 0 1-2 0V4.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 12 2m4 10H8a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2m-9 9v-3a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v3a1 1 0 0 1-2 0v-3a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v3a1 1 0 0 1-2 0");
}

</style>
