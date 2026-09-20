<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k334xmsnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-magnifying-glass-thin" /></template>
<style>
.k334xmsnu {
  fill: currentColor;
  d: path("M36 64a4 4 0 0 1 4-4h176a4 4 0 0 1 0 8H40a4 4 0 0 1-4-4m4 68h72a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8m88 56H40a4 4 0 0 0 0 8h88a4 4 0 0 0 0-8m106.83 6.83a4 4 0 0 1-5.66 0l-22.72-22.72a36.06 36.06 0 1 1 5.66-5.66l22.72 22.72a4 4 0 0 1 0 5.66M184 172a28 28 0 1 0-28-28a28 28 0 0 0 28 28");
}

</style>
