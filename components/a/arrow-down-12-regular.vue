<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n37fhvbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-12-regular" /></template>
<style>
.n37fhvbtl {
  fill: currentColor;
  d: path("M6 1.5a.5.5 0 0 1 .5.5v6.793l2.646-2.647a.5.5 0 1 1 .708.708l-3.5 3.5a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L5.5 8.793V2a.5.5 0 0 1 .5-.5");
}

</style>
