<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dtm1hnbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:copyleft-thin" /></template>
<style>
.dtm1hnbch {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92m44-92a44 44 0 0 1-79.2 26.41a4 4 0 0 1 6.4-4.81a36 36 0 1 0 0-43.2a4 4 0 0 1-6.4-4.81A44 44 0 0 1 172 128");
}

</style>
