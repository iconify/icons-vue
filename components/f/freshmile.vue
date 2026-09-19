<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7ujgtb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freshmile" /></template>
<style>
.d7ujgtb9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.25A9.25 9.25 0 1 1 14.75 24H24zm0-18.5A9.25 9.25 0 1 1 33.25 24H24z");
}

</style>
