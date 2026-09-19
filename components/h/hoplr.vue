<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rkoeh_zlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hoplr" /></template>
<style>
.rkoeh_zlx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.26 43.5h18.983a6.69 6.69 0 0 0 6.69-6.689V21.153A7.3 7.3 0 0 0 37.5 15.72L25.652 5.13a2.483 2.483 0 0 0-3.304 0L10.906 15.365A8.5 8.5 0 0 0 8.068 21.7v15.608A6.19 6.19 0 0 0 14.26 43.5");
}

</style>
