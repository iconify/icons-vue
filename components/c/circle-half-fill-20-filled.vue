<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oep2_1mtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-half-fill-20-filled" /></template>
<style>
.oep2_1mtc {
  fill: currentColor;
  d: path("M3.5 10a6.5 6.5 0 0 1 13 0zM10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
