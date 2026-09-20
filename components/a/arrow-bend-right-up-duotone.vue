<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="s-nrecbfb"/><path class="em9cikb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-right-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em9cikb4d {
  d: path("m205.66 74.34l-48-48a8 8 0 0 0-11.32 0l-48 48A8 8 0 0 0 104 88h40v40a88.1 88.1 0 0 1-88 88a8 8 0 0 0 0 16a104.11 104.11 0 0 0 104-104V88h40a8 8 0 0 0 5.66-13.66M123.31 72L152 43.31L180.69 72Z");
}

.s-nrecbfb {
  d: path("M200 80h-96l48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
