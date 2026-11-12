<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuyi5rb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circuit-board-fill" /></template>
<style>
.fuyi5rb1j {
  fill: currentColor;
  d: path("M16 2v5a.997.997 0 0 1-1 1h-3.171a3 3 0 1 0 0 2H15a3 3 0 0 0 3-3V2h1a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H8v-5a.997.997 0 0 1 1-1h3.171a3 3 0 1 0 0-2H9a3 3 0 0 0-3 3v5H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

</style>
