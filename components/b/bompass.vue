<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="sfd2fvpyg"/><path class="uncznvcae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bompass" /></template>
<style>
.sfd2fvpyg {
  cx: 24.039px;
  cy: 23.76px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uncznvcae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.611 10.373v8.131l-7.057 4.1l.017-8.163zM15.389 34.977l4-6.928l.59 9.578l4-6.928");
}

</style>
