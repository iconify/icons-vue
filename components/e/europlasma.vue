<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4s40v6hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:europlasma" /></template>
<style>
.z4s40v6hc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c2.776 12.263 11.973 17.339 11.973 28.044C35.973 42.696 25.646 43.5 24 43.5s-11.973-.804-11.973-10.956C12.027 21.839 21.224 16.763 24 4.5");
}

</style>
