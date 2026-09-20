<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rb5rk_bng"/><path class="byy-1rndk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-up-left-duotone" /></template>
<style>
.byy-1rndk {
  d: path("M128 96H88V56a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 88 152v-40h40a88.1 88.1 0 0 1 88 88a8 8 0 0 0 16 0A104.11 104.11 0 0 0 128 96m-56 36.69L43.31 104L72 75.31Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rb5rk_bng {
  d: path("M80 56v96l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
