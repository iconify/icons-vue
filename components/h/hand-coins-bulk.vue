<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ineq4kbma"/><path class="junl4abra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-coins-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ineq4kbma {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.293 15.293l3-3C7.049 11.537 7.896 11 9 11h3c.942 0 1.827.439 2.394 1.191l1.899-1.898a3.121 3.121 0 1 1 4.414 4.414l-5 5C14.992 20.422 14.039 21 13 21H8a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 0-1.414");
}

.junl4abra {
  d: path("M13.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7 1a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M12 17h-2a1 1 0 0 1 0-2h2a.997.997 0 0 0 1-1a1 1 0 0 1 2 0a3 3 0 0 1-3 3m-8.293-2.707l6 6a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414");
}

</style>
