<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq1dffb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:1k-plus-sharp" /></template>
<style>
.pq1dffb9d {
  fill: currentColor;
  d: path("M16.73 13.885h.77v-1.5H19v-.77h-1.5v-1.5h-.77v1.5h-1.5v.77h1.5zm-5.691.807h.884v-2.365l2.288 2.365h1.212l-2.634-2.73l2.634-2.654H14.25l-2.327 2.326V9.308h-.885zm-3.078 0h.885V9.308H6.462v.884h1.5zM4 20V4h16v16z");
}

</style>
