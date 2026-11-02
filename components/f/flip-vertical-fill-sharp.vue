<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csg3uh9id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-fill-sharp" /></template>
<style>
.csg3uh9id {
  fill: currentColor;
  d: path("M6.293 3.707A1 1 0 0 1 7 2h10a1.002 1.002 0 0 1 .707 1.707l-5 5a1 1 0 0 1-1.414 0ZM7 13H5a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m6-2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2ZM6.293 20.293l5-5a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 17 22H7a1.002 1.002 0 0 1-.707-1.707");
}

</style>
