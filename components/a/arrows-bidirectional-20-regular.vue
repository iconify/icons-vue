<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oqsla_bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrows-bidirectional-20-regular" /></template>
<style>
.oqsla_bka {
  fill: currentColor;
  d: path("M6.678 5.033A.5.5 0 0 1 7 5.5V8h6V5.5a.5.5 0 0 1 .874-.332l4 4.5a.5.5 0 0 1 0 .664l-4 4.5A.5.5 0 0 1 13 14.5V12H7v2.5a.5.5 0 0 1-.874.332l-4-4.5a.5.5 0 0 1 0-.664l4-4.5a.5.5 0 0 1 .552-.135M3.169 10L6 13.185V11.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v1.685L16.831 10L14 6.815V8.5a.5.5 0 0 1-.5.5h-7a.5.5 0 0 1-.5-.5V6.815z");
}

</style>
