<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vv_cg5cwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dailypay" /></template>
<style>
.vv_cg5cwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.393 36.802a15 15 0 0 1 0-21.213a15 15 0 0 1 21.213 0a15 15 0 0 1 0 21.213m-30.106 0h39");
}

</style>
