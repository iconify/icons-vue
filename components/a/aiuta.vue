<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zyjiftgfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aiuta" /></template>
<style>
.zyjiftgfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 15.525A3.5 3.5 0 1 1 26.475 18l-1.738 1.738c-.664.86.017 1.29 4.323 4.759L43.5 35.975M22 22.475l-17.5 13.5M37 30.808H11.198");
}

</style>
