<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eu2kaj4gp"/><path class="vgn00vb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eu2kaj4gp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h8a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13");
}

.vgn00vb9a {
  d: path("M14.315 4.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114M9.414 10H13a1 1 0 0 1 0 2H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414Zm6.743-3.222a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
