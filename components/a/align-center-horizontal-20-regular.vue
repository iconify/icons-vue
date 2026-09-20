<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ta5vrkb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-center-horizontal-20-regular" /></template>
<style>
.ta5vrkb4v {
  fill: currentColor;
  d: path("M18 9.5a.5.5 0 0 1-.5.5H16v2a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2v-2H9v4a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-4H2.5a.5.5 0 0 1 0-1H4V5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v4h2V7a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v2h1.5a.5.5 0 0 1 .5.5M5 14a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1H6a1 1 0 0 0-1 1zm7-2a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1h-1a1 1 0 0 0-1 1z");
}

</style>
