<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is6sl663b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-vent-fill-sharp" /></template>
<style>
.is6sl663b {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm5 14V7a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0m4 0V7a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0M21 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
