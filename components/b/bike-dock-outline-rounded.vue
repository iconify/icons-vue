<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbk5nob4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bike-dock-outline-rounded" /></template>
<style>
.nbk5nob4b {
  fill: currentColor;
  d: path("M3.95 21q-.425 0-.687-.325T3 19.925t.25-.737t.65-.438l3.35-.95L8.775 4.775q.1-.75.663-1.263T10.775 3H13.2q.775 0 1.338.513t.662 1.262L16.725 17.8l3.325.95q.425.125.688.425T21 19.9q0 .45-.288.775T20 21zM11 18h2V6q0-.425-.288-.712T12 5t-.712.288T11 6z");
}

</style>
