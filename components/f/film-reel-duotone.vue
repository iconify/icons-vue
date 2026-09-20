<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="nmbbewghm"/><path class="o_pfao8rj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:film-reel-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nmbbewghm {
  d: path("M128 32a96 96 0 1 0 96 96a96 96 0 0 0-96-96M80 144a16 16 0 1 1 16-16a16 16 0 0 1-16 16m48 48a16 16 0 1 1 16-16a16 16 0 0 1-16 16m0-96a16 16 0 1 1 16-16a16 16 0 0 1-16 16m48 48a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o_pfao8rj {
  d: path("M232 216h-48.64A103.95 103.95 0 1 0 128 232h104a8 8 0 0 0 0-16M40 128a88 88 0 1 1 88 88a88.1 88.1 0 0 1-88-88m88-24a24 24 0 1 0-24-24a24 24 0 0 0 24 24m0-32a8 8 0 1 1-8 8a8 8 0 0 1 8-8m24 104a24 24 0 1 0-24 24a24 24 0 0 0 24-24m-32 0a8 8 0 1 1 8 8a8 8 0 0 1-8-8m56-24a24 24 0 1 0-24-24a24 24 0 0 0 24 24m0-32a8 8 0 1 1-8 8a8 8 0 0 1 8-8m-96-16a24 24 0 1 0 24 24a24 24 0 0 0-24-24m0 32a8 8 0 1 1 8-8a8 8 0 0 1-8 8");
}

</style>
