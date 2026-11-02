<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjiq25bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-down-left-fill-sharp" /></template>
<style>
.rjiq25bbj {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m7 4h4a1 1 0 0 0 0-2h-1.586l4.293-4.293a.999.999 0 1 0-1.414-1.414L10 12.586V11a1 1 0 0 0-2 0v4a1 1 0 0 0 1 1");
}

</style>
