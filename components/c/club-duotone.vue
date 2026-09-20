<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hzv5xypza"/><path class="zu_h5h07y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:club-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hzv5xypza {
  d: path("M232 144a48 48 0 0 1-88.07 26.44L160 224H96l16.07-53.56a48 48 0 1 1-23.9-71.65a48 48 0 1 1 79.66 0A48 48 0 0 1 232 144");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zu_h5h07y {
  d: path("M184 88h-2.33a56 56 0 1 0-107.34 0H72a56 56 0 1 0 24.54 106.35l-8.2 27.35A8 8 0 0 0 96 232h64a8 8 0 0 0 7.66-10.3l-8.2-27.35A56 56 0 1 0 184 88m0 96a40 40 0 0 1-33.4-18a8 8 0 0 0-14.33 6.71l13 43.26h-42.5l13-43.26A8 8 0 0 0 105.4 166a40 40 0 1 1-19.93-59.71a8 8 0 0 0 9.33-12a40 40 0 1 1 66.4 0a8 8 0 0 0 9.33 12A40 40 0 1 1 184 184");
}

</style>
