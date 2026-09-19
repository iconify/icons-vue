<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ktq-3hbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blokk" /></template>
<style>
.ktq-3hbxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.77 5.5H18.23a4.57 4.57 0 0 0-3.232 1.339l-8.16 8.16A4.57 4.57 0 0 0 5.5 18.23v11.54a4.57 4.57 0 0 0 1.339 3.232l8.16 8.16A4.57 4.57 0 0 0 18.23 42.5h11.54a4.57 4.57 0 0 0 3.232-1.339l8.159-8.16A4.57 4.57 0 0 0 42.5 29.77V18.23a4.57 4.57 0 0 0-1.339-3.232l-8.16-8.159A4.57 4.57 0 0 0 29.77 5.5");
}

</style>
