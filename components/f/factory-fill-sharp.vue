<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lobodhb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:factory-fill-sharp" /></template>
<style>
.lobodhb1m {
  fill: currentColor;
  d: path("M4 20V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v7.234l3.486-2.091A.997.997 0 0 1 15 9v1.234l3.486-2.091A.997.997 0 0 1 20 9v11h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm4.01-5H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M16 15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
