<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ey84dcc7v"/><path class="iri2n936h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edevlet" /></template>
<style>
.ey84dcc7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.095 34.464C24.143 38.603 4.5 43.348 4.5 33.25c0-5.02 4.963-13.681 13.408-18.815c11.528-7.008 27.329-8.39 25.437.552c-2.614 12.352-23.212 20.462-27.2 16.001c-5.079-5.683 7.446-13.003 14.086-13.003");
}

.iri2n936h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.693 15.148l-1.477 2.873h3.02l-3.933 1.775l-1.477 2.873l-.954-1.775l-3.934 1.775l3.344-2.873l-.954-1.775h3.021z");
}

</style>
