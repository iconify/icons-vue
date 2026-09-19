<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqnfoi84c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbc-sounds" /></template>
<style>
.eqnfoi84c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.69 6.059H42.5v35.883H23.69zm-11.299 5.587H23.69v24.708H12.391zM5.5 16.55h6.891v14.899H5.5z");
}

</style>
