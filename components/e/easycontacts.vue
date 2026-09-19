<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="p2xmj80tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easycontacts" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p2xmj80tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.695 13.774c5.957-.011 8.95 7.188 4.742 11.404s-11.413 1.236-11.413-4.72a6.683 6.683 0 0 1 6.67-6.684zM10.341 40.543v-6.434c0-2.477 5.887-4.493 13.354-4.493s13.354 2.078 13.354 4.555v6.372");
}

</style>
