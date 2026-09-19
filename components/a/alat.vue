<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="emx8qkbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alat" /></template>
<style>
.emx8qkbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.49 11.859L43.5 36.141H32.521L24 21.39l-5.49-9.531L4.5 36.141h18.658");
}

</style>
