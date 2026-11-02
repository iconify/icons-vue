<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i6ba3ccbg"/><path class="j4qh7cpvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i6ba3ccbg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m16.894 10.553l3 6c.56 1.12.597 2.457.034 3.583a3.44 3.44 0 0 1-1.154 1.328A3.2 3.2 0 0 1 17 22H7a3.2 3.2 0 0 1-1.774-.536a3.44 3.44 0 0 1-1.154-1.328c-.563-1.126-.526-2.463.034-3.583l5-10a3.234 3.234 0 0 1 5.788 0Z");
}

.j4qh7cpvq {
  d: path("M15 8a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm3 6a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
