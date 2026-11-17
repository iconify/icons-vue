<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy45kfbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:glass-water-fill-sharp" /></template>
<style>
.cy45kfbra {
  fill: currentColor;
  d: path("M19 2a1 1 0 0 1 .994 1.11l-2 18A1 1 0 0 1 17 22H7a1 1 0 0 1-.994-.89l-2-18A1 1 0 0 1 5 2ZM6.895 11h10.21l.778-7H6.117Z");
}

</style>
