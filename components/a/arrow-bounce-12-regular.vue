<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d3nx0v55o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-12-regular" /></template>
<style>
.d3nx0v55o {
  fill: currentColor;
  d: path("M1 3.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1H2.707L6.5 7.793l3.646-3.647a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0L2 4.707V7.5a.5.5 0 0 1-1 0z");
}

</style>
