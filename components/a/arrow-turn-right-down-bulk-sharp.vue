<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4--iabsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-right-down-bulk-sharp" /></template>
<style>
.l4--iabsu {
  fill: currentColor;
  d: path("M16 6a1 1 0 0 1 1 1v7.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-5 5a1 1 0 0 1-1.414 0l-5-5a.999.999 0 1 1 1.414-1.414L15 14.586V8H3a1 1 0 0 1 0-2Z");
}

</style>
