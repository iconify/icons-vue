<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t_xuii4jo"/><path class="yss_bxb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-car-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.t_xuii4jo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 10h6a1 1 0 0 1 .724.31a8.25 8.25 0 0 1 0 11.38A1 1 0 0 1 15 22H9a1 1 0 0 1-.724-.31a8.25 8.25 0 0 1 0-11.38A1 1 0 0 1 9 10m-.919 5h7.838a6.25 6.25 0 0 0-1.367-3H9.448a6.25 6.25 0 0 0-1.367 3");
}

.yss_bxb-c {
  d: path("M14.01 2a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Zm-4 1a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm9.747 1.03a1 1 0 0 1 .486 1.94L13 7.781V11a1 1 0 0 1-2 0V8.281L4.243 9.97a1 1 0 0 1-.486-1.94Z");
}

</style>
