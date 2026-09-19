<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n5mosbb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:call-of-duty" /></template>
<style>
.n5mosbb-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 10.467v27.01l4.116 2.873l6.296-4.034l.003-25.145L8.7 7.651Zm39 0v27.01l-4.116 2.873l-6.296-4.034l-.003-25.145l6.215-3.52Zm-13.317 2.301v14.575L24 30.846l-6.184-3.503V12.768L24 16.27Z");
}

</style>
