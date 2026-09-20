<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="s9fjjhdqu"/><path class="ncg03rbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:layout-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ncg03rbnq {
  d: path("M216 40H40a16 16 0 0 0-16 16v144a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16m0 16v40H40V56ZM40 112h56v88H40Zm176 88H112v-88h104z");
}

.s9fjjhdqu {
  d: path("M104 104v104H40a8 8 0 0 1-8-8v-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
