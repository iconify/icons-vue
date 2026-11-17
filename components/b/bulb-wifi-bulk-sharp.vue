<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="loopsac4v"/><path class="y5ljebcju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-wifi-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.loopsac4v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 16.021V18a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.979c-.022-.075-.064-.144-.103-.211c-.147-.246-.328-.474-.502-.702C3.696 14.191 3 13.209 3 12a5 5 0 0 1 10 0c0 1.209-.696 2.191-1.395 3.108c-.174.228-.355.456-.502.702c-.039.067-.081.136-.103.211");
}

.y5ljebcju {
  d: path("M17.192 2.808a12.9 12.9 0 0 1 2.818 4.217A12.9 12.9 0 0 1 21 12a1 1 0 0 1-2 0a10.9 10.9 0 0 0-.837-4.21a10.9 10.9 0 0 0-2.385-3.568a1 1 0 0 1 1.414-1.414m-.877 5.748A8.9 8.9 0 0 1 17 12a1 1 0 0 1-2 0a6.9 6.9 0 0 0-.533-2.679A6.9 6.9 0 0 0 12.95 7.05a.997.997 0 0 1 0-1.414a1 1 0 0 1 1.414 0a8.9 8.9 0 0 1 1.951 2.92M10 20a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
