<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2vmljbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-eraser-sharp" /></template>
<style>
.u2vmljbko {
  fill: currentColor;
  d: path("M17.25 18H22v2h-6.75zm-12.5 2L1.2 16.45L15 2.15l7.8 7.8L13 20z");
}

</style>
