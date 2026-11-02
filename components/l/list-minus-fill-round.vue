<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7wu9kboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-minus-fill-round" /></template>
<style>
.y7wu9kboj {
  fill: currentColor;
  d: path("M3 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m12 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2M3 15h7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
