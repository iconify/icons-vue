<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="n_-6a96al"/><path class="d8m65ybkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chalkboard-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d8m65ybkx {
  d: path("M240 192h-8V56a16 16 0 0 0-16-16H40a16 16 0 0 0-16 16v136h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16M40 56h176v136h-16v-24a8 8 0 0 0-8-8h-72a8 8 0 0 0-8 8v24H72V88h112v48a8 8 0 0 0 16 0V80a8 8 0 0 0-8-8H64a8 8 0 0 0-8 8v112H40Zm144 136h-56v-16h56Z");
}

.n_-6a96al {
  d: path("M192 80v88h-72v32H64V80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
