<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="dbk5dnbas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-help-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dbk5dnbas {
  d: path("M9.236 11.832A3 3 0 1 1 12 16a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 13a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M12.01 17a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

</style>
