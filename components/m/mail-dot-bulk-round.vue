<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b9ovb6fnr"/><path class="na0b9wkmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-bulk-round" /></template>
<style>
.b9ovb6fnr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13v2a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h4a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13");
}

.cuyn6tgcc {
  fill: currentColor;
}

.na0b9wkmg {
  d: path("M14.315 4.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556m-8.45 2.515C8.263 9.848 9.252 10 10 10h3a1 1 0 0 1 0 2h-3c-1.317 0-2.748-.335-3.707-1.293l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

</style>
