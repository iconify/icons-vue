<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a9x0-pbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:artix-linux" /></template>
<style>
.a9x0-pbwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.5 5.5l-6.5 13l18 10zm19 37l-5.5-10l-10 5zm-37 0L15 23l18 7.5z");
}

</style>
