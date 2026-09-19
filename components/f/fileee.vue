<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-997dd2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fileee" /></template>
<style>
.f-997dd2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.284 22.437h15.819m-5.995 2.347V43.5l-8.729-18.716M24.658 4.5l-2.55 2.666v15.271M35.716 7.166L33.051 4.5h-6.045m8.711 6.933V9.514");
}

</style>
