<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qafg8hbfh"/><path class="jvz7jqb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lectio-365" /></template>
<style>
.jvz7jqb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.172 16.338L32.835 24l-7.663 7.663");
}

.qafg8hbfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.834 24H3.672m2.344 4.87v3.88a4 4 0 0 0 2 3.465l15.156 8.75a4 4 0 0 0 4 0l15.156-8.75a4 4 0 0 0 2-3.465v-17.5a4 4 0 0 0-2-3.465l-15.156-8.75a4 4 0 0 0-4 0l-15.156 8.75a4 4 0 0 0-2 3.465v3.88");
}

</style>
