<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bc0ft1biw"/><path class="r-rf-pbgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-bulk-round" /></template>
<style>
.bc0ft1biw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21H5a1 1 0 0 1-1-1V7a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4v13a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.r-rf-pbgq {
  d: path("m11.375 9.819l.113-.09A3.98 3.98 0 0 1 14 8.842c.675 0 1.339.17 1.931.496l.004.002q.298.165.563.378l1.626 1.3A4.99 4.99 0 0 1 20 14.923V19h1a1.002 1.002 0 0 1 .866 1.5c-.179.309-.509.5-.866.5H3a1 1 0 0 1 0-2h8v-8.386a1 1 0 0 1 .375-.795M18 14.922a2.99 2.99 0 0 0-1.126-2.342l-1.625-1.3A2 2 0 0 0 13 11.108V19h5Z");
}

</style>
