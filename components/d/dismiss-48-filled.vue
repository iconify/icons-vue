<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ikpza7gwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-48-filled" /></template>
<style>
.ikpza7gwb {
  fill: currentColor;
  d: path("M8.56 6.44a1.5 1.5 0 1 0-2.12 2.12L21.878 24L6.439 39.44a1.5 1.5 0 1 0 2.122 2.12L24 26.121L39.439 41.56a1.5 1.5 0 1 0 2.12-2.121L26.122 24l15.44-15.439A1.5 1.5 0 1 0 39.44 6.44L24 21.879z");
}

</style>
