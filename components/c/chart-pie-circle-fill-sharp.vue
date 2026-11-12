<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uagt6pe5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-circle-fill-sharp" /></template>
<style>
.uagt6pe5e {
  fill: currentColor;
  d: path("M21 13h-8v8a1 1 0 0 1-1 1a10 10 0 1 1 10-10a1 1 0 0 1-1 1m-7 5a4 4 0 1 1 8 0a4 4 0 0 1-8 0m2 0a2 2 0 1 0 3.999.001A2 2 0 0 0 16 18");
}

</style>
