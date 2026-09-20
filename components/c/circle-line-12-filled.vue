<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fg2i8dbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-line-12-filled" /></template>
<style>
.fg2i8dbhu {
  fill: currentColor;
  d: path("M1 6a5 5 0 0 1 10 0zm.1 1a5.002 5.002 0 0 0 9.8 0z");
}

</style>
