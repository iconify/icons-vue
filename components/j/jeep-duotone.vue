<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="i7ghkhrql"/><path class="rb8ygzbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:jeep-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i7ghkhrql {
  d: path("M224 96H32l10.65-49.68A8 8 0 0 1 50.47 40h155.06a8 8 0 0 1 7.82 6.32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rb8ygzbqn {
  d: path("M240 88h-9.53l-9.29-43.35A16.08 16.08 0 0 0 205.53 32H50.47a16.08 16.08 0 0 0-15.65 12.65L25.53 88H16a8 8 0 0 0 0 16h8v96a16 16 0 0 0 16 16h24a16 16 0 0 0 16-16v-24h96v24a16 16 0 0 0 16 16h24a16 16 0 0 0 16-16v-96h8a8 8 0 0 0 0-16M50.47 48h155.06l8.57 40H41.9ZM64 200H40v-24h24Zm128 0v-24h24v24Zm24-40h-64v-32a8 8 0 0 0-16 0v32h-16v-32a8 8 0 0 0-16 0v32H40v-56h176ZM56 132a12 12 0 1 1 12 12a12 12 0 0 1-12-12m120 0a12 12 0 1 1 12 12a12 12 0 0 1-12-12");
}

</style>
