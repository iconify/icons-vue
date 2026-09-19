<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2eh1tbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbc-iplayer" /></template>
<style>
.f2eh1tbmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.112 11.601h8.2v24.797h-8.2zm33.776 5.298L36.788 24L15.313 11.602l4.1-7.102zM19.413 43.5l-4.1-7.102L36.788 24l4.1 7.101z");
}

</style>
