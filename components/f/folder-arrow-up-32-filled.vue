<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2pp1rb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-arrow-up-32-filled" /></template>
<style>
.v2pp1rb9d {
  fill: currentColor;
  d: path("M2 8.5A4.5 4.5 0 0 1 6.5 4h3.964a3.5 3.5 0 0 1 2.475 1.025L15 7.085l-3.475 3.476a1.5 1.5 0 0 1-1.06.439H2zM2 13v10.5A4.5 4.5 0 0 0 6.5 28h10.016A9 9 0 0 1 30 16.292V12a4.5 4.5 0 0 0-4.501-4.5h-8.086l-4.475 4.475A3.5 3.5 0 0 1 10.464 13zm29.5 10a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0M25 20.06l2.72 2.72a.75.75 0 1 0 1.06-1.06l-4-4a.75.75 0 0 0-1.06 0l-4 4a.75.75 0 1 0 1.06 1.06l2.72-2.72v7.69a.75.75 0 0 0 1.5 0z");
}

</style>
