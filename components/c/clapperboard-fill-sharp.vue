<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv1i24bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-fill-sharp" /></template>
<style>
.zv1i24bno {
  fill: currentColor;
  d: path("m14.834 4.799l-.369-1.966l4.351-.816a1 1 0 0 1 1.167.799l.562 3a1 1 0 0 1-.798 1.167l-4.35.816Zm-5.518.017l-.185-.983l3.368-.632l.9 4.799H21a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9c0-.313.146-.608.396-.797l-.379-2.019a1 1 0 0 1 .799-1.167l4.35-.816L7.879 8h2.034Zm6.198 9.327l-5-3A.997.997 0 0 0 9 12v6a1 1 0 0 0 1.514.857l5-3a.997.997 0 0 0 0-1.714");
}

</style>
