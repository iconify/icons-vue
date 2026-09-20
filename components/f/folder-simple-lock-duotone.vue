<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="n8-ezvbjs"/><path class="by-ww5bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-simple-lock-duotone" /></template>
<style>
.by-ww5bxt {
  d: path("M232 88v16a8 8 0 0 1-16 0V88h-85.33a16.12 16.12 0 0 1-9.6-3.2L93.33 64H40v136h72a8 8 0 0 1 0 16H40a16 16 0 0 1-16-16V64a16 16 0 0 1 16-16h53.33a16.12 16.12 0 0 1 9.6 3.2L130.67 72H216a16 16 0 0 1 16 16m0 80v40a8 8 0 0 1-8 8h-72a8 8 0 0 1-8-8v-40a8 8 0 0 1 8-8h8v-4a28 28 0 0 1 56 0v4h8a8 8 0 0 1 8 8m-56-8h24v-4a12 12 0 0 0-24 0Zm40 16h-56v24h56Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.n8-ezvbjs {
  d: path("M224 168v40h-72v-40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
