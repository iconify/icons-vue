<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yteijjb7n"/><path class="dg4cnkbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-plus-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dg4cnkbge {
  d: path("M21 2v1h1a1 1 0 0 1 0 2h-1v1a1 1 0 0 1-2 0V5h-1a1 1 0 0 1 0-2h1V2a1 1 0 0 1 2 0M9 8h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6.293 5.293a4.66 4.66 0 0 0 6.586 0a1 1 0 1 1 1.414 1.414a6.656 6.656 0 0 1-9.414 0a.999.999 0 1 1 1.414-1.414");
}

.yteijjb7n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.276 2.263a1 1 0 0 1 .765 1.101a4.9 4.9 0 0 0 .227 2.251a4.94 4.94 0 0 0 1.196 1.921a4.94 4.94 0 0 0 1.921 1.196c.722.25 1.493.326 2.251.227a1 1 0 0 1 1.101.765a10 10 0 0 1-3.297 9.926a9.98 9.98 0 0 1-10.333 1.564A10 10 0 0 1 2.493 8.899a9.987 9.987 0 0 1 11.783-6.636");
}

</style>
