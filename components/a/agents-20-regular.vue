<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpiccgbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-20-regular" /></template>
<style>
.mpiccgbcy {
  fill: currentColor;
  d: path("M9.498 2a.5.5 0 1 1 0 1h-2.81a.75.75 0 0 0-.635.35L2.11 9.6a.75.75 0 0 0 0 .8l3.868 6.133c.183.29.503.467.846.467h.02a1 1 0 0 0 .967-.742l3.406-12.774A2 2 0 0 1 13.15 2h.02a2 2 0 0 1 1.692.934l3.868 6.132c.36.57.36 1.297 0 1.868l-3.94 6.25c-.321.508-.88.816-1.481.816h-2.81a.5.5 0 0 1 0-1h2.81a.75.75 0 0 0 .634-.35l3.942-6.25a.75.75 0 0 0 0-.8l-3.868-6.133A1 1 0 0 0 13.17 3h-.02a1 1 0 0 0-.966.742L8.778 16.516A2 2 0 0 1 6.846 18h-.02a2 2 0 0 1-1.692-.933l-3.868-6.133a1.75 1.75 0 0 1 0-1.868l3.941-6.25A1.75 1.75 0 0 1 6.687 2z");
}

</style>
