<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-893_zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-down-left-fill" /></template>
<style>
.g6-893_zu {
  fill: currentColor;
  d: path("m2.293 14.293l4-4a.999.999 0 1 1 1.414 1.414L5.414 14H19a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1h-8a1 1 0 0 1 0-2h8a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1-.009-1.405z");
}

</style>
