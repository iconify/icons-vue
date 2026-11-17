<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al2tf7bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-pause-three-quarter-fill-sharp" /></template>
<style>
.al2tf7bbj {
  fill: currentColor;
  d: path("M10.436 2.123a10 10 0 1 1-8.313 8.313a1 1 0 1 1 1.975.313a8 8 0 0 0 15.293 4.312a8 8 0 0 0-8.642-10.963a1 1 0 1 1-.313-1.975M3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122M11 15a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Z");
}

</style>
