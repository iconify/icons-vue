<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ccizyqbem"/><path class="msxm1u8st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boosteroid" /></template>
<style>
.ccizyqbem {
  cx: 30.5px;
  cy: 17.5px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.msxm1u8st {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.818 20.454L5.5 29.772m22.046 3.41L18.228 42.5M26 22l-9.318 9.318");
}

</style>
