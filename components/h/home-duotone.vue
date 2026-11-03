<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vyh8r-s4m"/><path clip-rule="evenodd" class="g5y9tjx1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g5y9tjx1a {
  fill-rule: evenodd;
  d: path("M9 20L9 16C9 14.8954 9.8954 14 11 14L13 14C14.1046 14 15 14.8954 15 16L15 20L9 20Z");
}

.vyh8r-s4m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0605 2.70707C11.1795 1.7591 12.8205 1.7591 13.9395 2.70707L20.9395 8.63773L21.0615 8.74808C21.6586 9.31297 22 10.1002 22 10.9268V19C21.9999 20.6568 20.6568 22 19 22H5C3.34318 22 2.00011 20.6568 2 19V10.9268C2.00002 10.0452 2.38775 9.20775 3.06055 8.63773L10.0605 2.70707Z");
}

</style>
