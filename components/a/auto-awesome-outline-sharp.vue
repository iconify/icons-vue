<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo_y38bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-awesome-outline-sharp" /></template>
<style>
.qo_y38bab {
  fill: currentColor;
  d: path("m19 9l-1.25-2.75L15 5l2.75-1.25L19 1l1.25 2.75L23 5l-2.75 1.25L19 9Zm0 14l-1.25-2.75L15 19l2.75-1.25L19 15l1.25 2.75L23 19l-2.75 1.25L19 23ZM9 20l-2.5-5.5L1 12l5.5-2.5L9 4l2.5 5.5L17 12l-5.5 2.5L9 20Zm0-4.85L10 13l2.15-1L10 11L9 8.85L8 11l-2.15 1L8 13l1 2.15ZM9 12Z");
}

</style>
