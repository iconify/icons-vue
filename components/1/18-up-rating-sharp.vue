<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3os2ybrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:18-up-rating-sharp" /></template>
<style>
.h3os2ybrl {
  fill: currentColor;
  d: path("M8.808 14.692h.884V9.308H7.308v.884h1.5zm3 0h3.884V9.308h-3.884zm.884-.769v-1.538h2.116v1.538zm0-2.307v-1.539h2.116v1.539zM4 20V4h16v16z");
}

</style>
