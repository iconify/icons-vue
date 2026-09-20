<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wv6q-kw2f"/><path class="h-d3cubvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h-d3cubvh {
  d: path("M216 120h-96V56a8 8 0 0 0-13.66-5.66l-72 72a8 8 0 0 0 0 11.32l72 72A8 8 0 0 0 120 200v-64h96a8 8 0 0 0 0-16m-112 60.69L51.31 128L104 75.31Z");
}

.wv6q-kw2f {
  d: path("M112 56v144l-72-72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
