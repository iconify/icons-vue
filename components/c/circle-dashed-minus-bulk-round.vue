<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ls6shcckx"/><path class="t02sidbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-minus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ls6shcckx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 11h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

.t02sidbcr {
  d: path("M13.564 2.123a.999.999 0 1 1-.313 1.975a8 8 0 0 0-2.502 0a1 1 0 1 1-.313-1.975a10 10 0 0 1 3.128 0M6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122A10 10 0 0 1 6.122 3.91M20.09 6.122a1 1 0 1 1-1.618 1.176a8 8 0 0 0-1.77-1.77a1 1 0 1 1 1.176-1.618a10 10 0 0 1 2.212 2.212M2.123 10.436a.999.999 0 1 1 1.975.313a8 8 0 0 0 0 2.502a1 1 0 1 1-1.975.313a10 10 0 0 1 0-3.128m19.754 3.128a1 1 0 0 1-1.975-.313a8 8 0 0 0 0-2.502a1 1 0 1 1 1.975-.313a10 10 0 0 1 0 3.128M3.91 17.878a1 1 0 1 1 1.618-1.176a8 8 0 0 0 1.77 1.77a1 1 0 1 1-1.176 1.618a10 10 0 0 1-2.212-2.212m13.968 2.212a1 1 0 1 1-1.176-1.618a8 8 0 0 0 1.77-1.77a1 1 0 1 1 1.618 1.176a10 10 0 0 1-2.212 2.212m-7.442 1.787a1 1 0 0 1 .313-1.975a8 8 0 0 0 2.502 0a1 1 0 1 1 .313 1.975a10 10 0 0 1-3.128 0");
}

</style>
