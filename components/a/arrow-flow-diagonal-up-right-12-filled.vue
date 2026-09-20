<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="djxl3zllx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-diagonal-up-right-12-filled" /></template>
<style>
.djxl3zllx {
  fill: currentColor;
  d: path("M6 1.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V2.707L5.586 7.121a2.5 2.5 0 1 1-.707-.707L9.293 2H6.5a.5.5 0 0 1-.5-.5");
}

</style>
