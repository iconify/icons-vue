<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="im0tfoboq"/><path class="s9kh3_84c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-kzt-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.im0tfoboq {
  d: path("M200 56v40H56V56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s9kh3_84c {
  d: path("M208 96a8 8 0 0 1-8 8h-64v112a8 8 0 0 1-16 0V104H56a8 8 0 0 1 0-16h144a8 8 0 0 1 8 8M56 64h144a8 8 0 0 0 0-16H56a8 8 0 0 0 0 16");
}

</style>
