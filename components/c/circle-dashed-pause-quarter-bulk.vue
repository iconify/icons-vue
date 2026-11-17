<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xu7tjvb8r"/><path class="w455zabrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-pause-quarter-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.w455zabrf {
  d: path("M12 2a9.9 9.9 0 0 1 3.827.761a9.984 9.984 0 0 1 6.05 10.803a1 1 0 0 1-1.144.832a1 1 0 0 1-.831-1.145Q20 12.63 20 12a7.9 7.9 0 0 0-.609-3.061a7.9 7.9 0 0 0-1.734-2.596a7.98 7.98 0 0 0-6.908-2.245a1 1 0 1 1-.313-1.975A10 10 0 0 1 12 2M6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122A10 10 0 0 1 6.122 3.91m-3.999 6.526a.999.999 0 1 1 1.975.313a8 8 0 0 0 0 2.502a1 1 0 1 1-1.975.313a10 10 0 0 1 0-3.128m1.787 7.442a1 1 0 1 1 1.618-1.176a8 8 0 0 0 1.77 1.77a1 1 0 1 1-1.176 1.618a10 10 0 0 1-2.212-2.212m13.968 2.212a1 1 0 1 1-1.176-1.618a8 8 0 0 0 1.77-1.77a1 1 0 1 1 1.618 1.176a10 10 0 0 1-2.212 2.212m-8.095 1.387a1 1 0 0 1 .966-1.575a8 8 0 0 0 2.502 0a1 1 0 1 1 .313 1.975a10 10 0 0 1-3.128 0a1 1 0 0 1-.653-.4");
}

.xu7tjvb8r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 15a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Z");
}

</style>
