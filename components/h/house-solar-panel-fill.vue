<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x370h7o7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-solar-panel-fill" /></template>
<style>
.x370h7o7p {
  fill: currentColor;
  d: path("M3 19v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3m13 0a1 1 0 0 0 .992-1.124l-1-8A1 1 0 0 0 15 9H9a1 1 0 0 0-.992.876l-1 8A.997.997 0 0 0 8 19Zm-5-8v2H9.633l.25-2Zm2 2v-2h1.117l.25 2Zm-2 2v2H9.133l.25-2Zm2 2v-2h1.617l.25 2Z");
}

</style>
