<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pcp06pqxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:building-thin" /></template>
<style>
.pcp06pqxp {
  fill: currentColor;
  d: path("M232 228h-28V28h12a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8h12v200H24a4 4 0 0 0 0 8h208a4 4 0 0 0 0-8M60 28h136v200h-40v-44a4 4 0 0 0-4-4h-48a4 4 0 0 0-4 4v44H60Zm88 200h-40v-40h40ZM92 64a4 4 0 0 1 4-4h16a4 4 0 0 1 0 8H96a4 4 0 0 1-4-4m48 0a4 4 0 0 1 4-4h16a4 4 0 0 1 0 8h-16a4 4 0 0 1-4-4m-48 40a4 4 0 0 1 4-4h16a4 4 0 0 1 0 8H96a4 4 0 0 1-4-4m48 0a4 4 0 0 1 4-4h16a4 4 0 0 1 0 8h-16a4 4 0 0 1-4-4m-44 44a4 4 0 0 1 0-8h16a4 4 0 0 1 0 8Zm44-4a4 4 0 0 1 4-4h16a4 4 0 0 1 0 8h-16a4 4 0 0 1-4-4");
}

</style>
