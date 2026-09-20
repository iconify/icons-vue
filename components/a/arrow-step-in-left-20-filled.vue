<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vrmvg0bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-left-20-filled" /></template>
<style>
.vrmvg0bbo {
  fill: currentColor;
  d: path("M4 12a2 2 0 1 1 0-4a2 2 0 0 1 0 4m14-2a.5.5 0 0 1-.5.5H9.707l3.147 3.146a.5.5 0 0 1-.708.708l-4-4a.5.5 0 0 1 0-.708l4-4a.5.5 0 0 1 .708.708L9.707 9.5H17.5a.5.5 0 0 1 .5.5");
}

</style>
