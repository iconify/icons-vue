<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="nvjq80alh"/><path class="bmehlh09n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:file-ini-duotone" /></template>
<style>
.bmehlh09n {
  d: path("M48 152v56a8 8 0 0 1-16 0v-56a8 8 0 0 1 16 0m72-8a8 8 0 0 0-8 8v31l-25.49-35.65A8 8 0 0 0 72 152v56a8 8 0 0 0 16 0v-31l25.49 35.69A8 8 0 0 0 120 216a7.9 7.9 0 0 0 2.44-.38A8 8 0 0 0 128 208v-56a8 8 0 0 0-8-8m40 0a8 8 0 0 0-8 8v56a8 8 0 0 0 16 0v-56a8 8 0 0 0-8-8m56-56v136a8 8 0 0 1-16 0V96h-48a8 8 0 0 1-8-8V40H56v72a8 8 0 0 1-16 0V40a16 16 0 0 1 16-16h96a8 8 0 0 1 5.66 2.34l56 56A8 8 0 0 1 216 88m-56-8h28.69L160 51.31Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.nvjq80alh {
  d: path("M208 88h-56V32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
