<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v9nak9bvl"/><path class="kl6rj1bdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-1-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kl6rj1bdd {
  d: path("M8 5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-4a1 1 0 0 1 0-2h4a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-8a.997.997 0 0 0-1 1v4a1 1 0 0 1-2 0Z");
}

.v9nak9bvl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
