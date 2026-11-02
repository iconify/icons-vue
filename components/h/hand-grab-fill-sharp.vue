<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy610kn7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-grab-fill-sharp" /></template>
<style>
.zy610kn7a {
  fill: currentColor;
  d: path("M12 7a2 2 0 0 1 1.997-2h.006A2 2 0 0 1 16 7v5h1V9a1.999 1.999 0 0 1 3.001-1.732C20.619 7.626 21 8.285 21 9v6a7 7 0 0 1-7 7h-4a7 7 0 0 1-7-7v-3a3 3 0 0 1 3-3v6h1V9a1.999 1.999 0 0 1 3.001-1.732C10.619 7.626 11 8.285 11 9v3h1Z");
}

</style>
