<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ze2j_ac5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gender-intersex-fill" /></template>
<style>
.ze2j_ac5o {
  fill: currentColor;
  d: path("M147.91 113.72a28 28 0 1 1-25.63-25.63a28 28 0 0 1 25.63 25.63M216 40v176a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V40a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16m-28 16a8 8 0 0 0-8-8h-27.73a8.17 8.17 0 0 0-8.27 7.47a8 8 0 0 0 8 8.53h8.69l-15.77 15.77A44 44 0 1 0 112 159.26V176H92.27a8.17 8.17 0 0 0-8.27 7.47a8 8 0 0 0 8 8.53h20v15.73a8.18 8.18 0 0 0 7.47 8.25a8 8 0 0 0 8.53-8V192h19.73a8.17 8.17 0 0 0 8.25-7.47a8 8 0 0 0-8-8.53H128v-16.74a44 44 0 0 0 28.24-68.18L172 75.31v8.42a8.18 8.18 0 0 0 7.47 8.27a8 8 0 0 0 8.53-8Z");
}

</style>
