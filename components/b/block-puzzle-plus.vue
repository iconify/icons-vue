<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fy_-t9nqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:block-puzzle-plus" /></template>
<style>
.fy_-t9nqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5H11.667v12.333H24zm12.333 0H24v12.333h12.333zM24 17.833H11.667v12.334H24zm0 12.334H11.667V42.5H24z");
}

</style>
