<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxd6jzb8s"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:currency-bitcoin" /></template>
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

.vxd6jzb8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.53 24a4.399 4.399 0 0 1 0 8.797h-7.258V15.203h7.257a4.399 4.399 0 0 1 0 8.797m0 0h-7.257m0 8.797h-2.2m2.2-17.594h-2.2m4.399 19.793v-2.199m4.398 2.199v-2.199m-4.398-17.594v-2.199m4.398 2.199v-2.199");
}

</style>
