<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prclnzb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edgesensor-high-outline-sharp" /></template>
<style>
.prclnzb7w {
  fill: currentColor;
  d: path("M6 21V3h12v18zm10-2V5H8v14zM12.713 7.713Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288M0 17v-7h2v7zm3-3V7h2v7zm19 0V7h2v7zm-3 3v-7h2v7zM8 5v14z");
}

</style>
