<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jhbc_s6of"/><path class="btel8jwml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-bulk-round" /></template>
<style>
.btel8jwml {
  d: path("M9 7h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m11 6v6h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h15v-6a3 3 0 0 0-3-3a1 1 0 0 1 0-2a5 5 0 0 1 3.536 1.464A4.97 4.97 0 0 1 20 13M9 11h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jhbc_s6of {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 21a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v12a1 1 0 0 1-1 1ZM9 9h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2m0 4h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
