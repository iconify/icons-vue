<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aemd2-dei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-down-left-bulk-sharp" /></template>
<style>
.aemd2-dei {
  fill: currentColor;
  d: path("m2.293 14.293l4-4a.999.999 0 1 1 1.414 1.414L5.414 14H20V6h-9a1 1 0 0 1 0-2h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H5.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1-.009-1.405z");
}

</style>
