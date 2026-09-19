<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqbbopv3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gag" /></template>
<style>
.rqbbopv3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 4.5l16 8.05v22.9l-16 8l-16-8V28l16 8l9.42-4.75v-8L24 28L8 20v-7.45Zm0 7.42l-8.62 4.34L24 20.61l8.62-4.35Z");
}

</style>
