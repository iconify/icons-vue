<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcievoz4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-pause-half-fill-sharp" /></template>
<style>
.lcievoz4q {
  fill: currentColor;
  d: path("M10.436 2.123a10 10 0 1 1 0 19.754a1 1 0 1 1 .313-1.975a7.999 7.999 0 0 0 6.444-13.987a7.99 7.99 0 0 0-6.444-1.817a1 1 0 1 1-.313-1.975M3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122M11 9v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m4 0v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0M2.123 13.564a10 10 0 0 1 0-3.128a1 1 0 0 1 1.975.313a8 8 0 0 0 0 2.502a1 1 0 1 1-1.975.313m3.999 6.526a10 10 0 0 1-2.212-2.212a1 1 0 1 1 1.618-1.176a8 8 0 0 0 1.77 1.77a1.002 1.002 0 0 1-1.176 1.618");
}

</style>
