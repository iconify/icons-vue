<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tz5qexbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aimp" /></template>
<style>
.tz5qexbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.11 33.07zH16.86L24 21.22l10.92 18.14h7.58L24 8.64L5.5 39.36h25.4z");
}

</style>
