<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eu2kaj4gp"/><path class="csyf9-b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-bulk-sharp" /></template>
<style>
.csyf9-b8j {
  d: path("M14 6a4 4 0 1 1 8 0a4 4 0 0 1-8 0M3.707 4.293L9.414 10H13a1 1 0 0 1 0 2H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414M16 6a2 2 0 1 0 3.999.001A2 2 0 0 0 16 6");
}

.cuyn6tgcc {
  fill: currentColor;
}

.eu2kaj4gp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h8a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13");
}

</style>
