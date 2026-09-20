<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vziog9bmd"/><path class="q9b7nwxtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-right-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q9b7nwxtc {
  d: path("m221.66 74.34l-48-48a8 8 0 0 0-11.32 0l-48 48A8 8 0 0 0 120 88h40v80a48 48 0 0 1-96 0V80a8 8 0 0 0-16 0v88a64 64 0 0 0 128 0V88h40a8 8 0 0 0 5.66-13.66M139.31 72L168 43.31L196.69 72Z");
}

.vziog9bmd {
  d: path("M216 80h-96l48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
