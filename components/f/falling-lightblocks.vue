<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jtywnqb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:falling-lightblocks" /></template>
<style>
.jtywnqb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 4.5h13v13H11zm0 13h13v13H11zm0 13h13v13H11zm13 0h13v13H24z");
}

</style>
