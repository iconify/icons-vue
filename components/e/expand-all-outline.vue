<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8qdjqbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-all-outline" /></template>
<style>
.o8qdjqbdn {
  fill: currentColor;
  d: path("m12 22l-6-6l1.425-1.425L12 19.15l4.575-4.575L18 16zM7.45 9.4L6 8l6-6l6 6l-1.45 1.4L12 4.85z");
}

</style>
