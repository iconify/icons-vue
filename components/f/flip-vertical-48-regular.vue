<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cuykahaos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-48-regular" /></template>
<style>
.cuykahaos {
  fill: currentColor;
  d: path("M39.423 4.197c.36.23.577.627.577 1.053v15.5c0 .69-.56 1.25-1.25 1.25H5.25a1.25 1.25 0 0 1-.525-2.384l33.5-15.5a1.25 1.25 0 0 1 1.198.08M10.928 19.5H37.5V7.206zM40 43a1 1 0 0 1-1.425.905l-34-16A1 1 0 0 1 5 26h34a1 1 0 0 1 1 1z");
}

</style>
