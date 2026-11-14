<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mab27ccjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-28-regular" /></template>
<style>
.mab27ccjp {
  fill: currentColor;
  d: path("M25.251 22a.75.75 0 0 1 0 1.5H2.754a.75.75 0 0 1 0-1.5zm0-6a.75.75 0 0 1 0 1.5H2.754a.75.75 0 0 1 0-1.5zm0-6a.75.75 0 0 1 0 1.5H2.754a.75.75 0 0 1 0-1.5zm0-6a.75.75 0 0 1 0 1.5H2.754a.75.75 0 1 1 0-1.5z");
}

</style>
