<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyw334b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leboncoin-alt" /></template>
<style>
.dyw334b7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.78A4.22 4.22 0 0 0 19.78 24v21l25.27-25.22m0 0H24M45.5 24A21.5 21.5 0 1 1 24 2.5A21.51 21.51 0 0 1 45.5 24");
}

</style>
