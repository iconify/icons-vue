<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4q5z48ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:10k-sharp" /></template>
<style>
.x4q5z48ee {
  fill: currentColor;
  d: path("M6 15h1.5V9H5v1.5h1zm2.5 0H13V9H8.5zm1.5-1.5v-3h1.5v3zm4 1.5h1.5v-2.25L17.25 15H19l-2.25-3L19 9h-1.75l-1.75 2.25V9H14zM3 21V3h18v18z");
}

</style>
