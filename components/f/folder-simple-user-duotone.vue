<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rjyehobsy"/><path class="g56mx7pcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-simple-user-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g56mx7pcj {
  d: path("M214.61 198.62a32 32 0 1 0-45.23 0a40 40 0 0 0-17.11 23.32a8 8 0 0 0 5.67 9.79a8.2 8.2 0 0 0 2.06.27a8 8 0 0 0 7.73-5.95C170.56 215.42 180.54 208 192 208s21.44 7.42 24.27 18.05a8 8 0 1 0 15.46-4.11a40 40 0 0 0-17.12-23.32M192 160a16 16 0 1 1-16 16a16 16 0 0 1 16-16m40-72v32a8 8 0 0 1-16 0V88h-85.33a16.12 16.12 0 0 1-9.6-3.2L93.33 64H40v136h80a8 8 0 0 1 0 16H40a16 16 0 0 1-16-16V64a16 16 0 0 1 16-16h53.33a16.12 16.12 0 0 1 9.6 3.2L130.67 72H216a16 16 0 0 1 16 16");
}

.rjyehobsy {
  d: path("M216 176a24 24 0 1 1-24-24a24 24 0 0 1 24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
