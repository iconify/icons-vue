<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rndi--qtj"/><path clip-rule="evenodd" class="ognrjnbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ognrjnbei {
  fill-rule: evenodd;
  d: path("M9 20L9 14L15 14L15 20L9 20Z");
}

.rndi--qtj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.61 9.21C21.86 9.4 22 9.69 22 10V21C22 21.55 21.55 22 21 22H3C2.45 22 2 21.55 2 21V10C2 9.69 2.14 9.4 2.39 9.21L11.39 2.21C11.75 1.93 12.25 1.93 12.61 2.21L21.61 9.21Z");
}

</style>
