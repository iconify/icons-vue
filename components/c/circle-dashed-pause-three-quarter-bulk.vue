<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xu7tjvb8r"/><path class="rvtv2acwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-pause-three-quarter-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rvtv2acwz {
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a10 10 0 0 1-9.877-11.564a1 1 0 1 1 1.975.313a8 8 0 1 0 6.651-6.651a1 1 0 1 1-.313-1.975A10 10 0 0 1 12 2M6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122A10 10 0 0 1 6.122 3.91");
}

.xu7tjvb8r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 15a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Z");
}

</style>
