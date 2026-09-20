<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vtefvtb6n"/><path class="tz-4lebcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-double-up-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tz-4lebcl {
  d: path("M85.66 146.34a8 8 0 0 1-11.32 11.32l-48-48a8 8 0 0 1 0-11.32l48-48a8 8 0 0 1 11.32 11.32L43.31 104ZM232 200a8 8 0 0 1-16 0a88.11 88.11 0 0 0-80-87.63V152a8 8 0 0 1-13.66 5.66l-48-48a8 8 0 0 1 0-11.32l48-48A8 8 0 0 1 136 56v40.3A104.15 104.15 0 0 1 232 200M120 75.31L91.31 104L120 132.69Z");
}

.vtefvtb6n {
  d: path("M128 56v96l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
