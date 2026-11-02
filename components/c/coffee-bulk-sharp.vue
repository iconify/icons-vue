<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g_29lqbju"/><path class="aretu2cvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-bulk-sharp" /></template>
<style>
.aretu2cvj {
  d: path("m7.894 4.447l-1 2a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894m3 2a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894Zm5-2l-1 2a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894M17 9h2a3 3 0 1 1 0 6h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 0-2h-2a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g_29lqbju {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13V9a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v4a8 8 0 0 1-16 0");
}

</style>
