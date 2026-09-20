<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wwzb_vbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:goodreads-logo-light" /></template>
<style>
.wwzb_vbxr {
  fill: currentColor;
  d: path("M184 26a6 6 0 0 0-6 6v19.4A62 62 0 0 0 66 88v24a62 62 0 0 0 112 36.6V168a50.06 50.06 0 0 1-50 50c-17.09 0-34-8.41-43.08-21.43a6 6 0 1 0-9.84 6.86C86.34 219.57 107.11 230 128 230a62.07 62.07 0 0 0 62-62V32a6 6 0 0 0-6-6m-56 136a50.06 50.06 0 0 1-50-50V88a50 50 0 0 1 100 0v24a50.06 50.06 0 0 1-50 50");
}

</style>
