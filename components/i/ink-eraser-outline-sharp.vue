<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db47-nbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-eraser-outline-sharp" /></template>
<style>
.db47-nbmf {
  fill: currentColor;
  d: path("M17.25 18H22v2h-6.75zm-12.5 2L1.2 16.45L15 2.15l7.8 7.8L13 20zm7.4-2L20 9.95L15.05 5L4 16.4L5.6 18zM12 12");
}

</style>
