<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j16239xgd"/><circle class="r8hrpllxm"/><circle class="u6o06qkfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bahnbonus" /></template>
<style>
.j16239xgd {
  cx: 12.686px;
  cy: 13.571px;
  r: 8.186px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r8hrpllxm {
  cx: 33.081px;
  cy: 21.382px;
  r: 10.418px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u6o06qkfh {
  cx: 21.929px;
  cy: 37.417px;
  r: 5.198px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
