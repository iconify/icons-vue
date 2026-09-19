<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h9r27b6ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:disky" /></template>
<style>
.h9r27b6ce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.82 40.429A21.5 21.5 0 1 1 22.127 2.541m3.747-.001a21.5 21.5 0 0 1 14.597 35.24");
}

</style>
