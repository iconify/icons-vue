<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pyw3_vngm"/><path class="dlv_13btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:discord-alt-7" /></template>
<style>
.dlv_13btg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.08 23.395a3.34 3.34 0 0 0-1.583 2.835a3.35 3.35 0 0 0 6.7 0c0-.621-.18-1.195-.475-1.694zm15.84 0a3.34 3.34 0 0 1 1.583 2.835a3.35 3.35 0 0 1-6.7 0c0-.621.18-1.195.475-1.694z");
}

.pyw3_vngm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.59 34.173A49 49 0 0 1 14.68 38C7.3 37.79 4.5 33 4.5 33a44.8 44.8 0 0 1 4.81-19.52A16.47 16.47 0 0 1 18.69 10l1 2.31A33 33 0 0 1 24 12a33 33 0 0 1 4.33.3l1-2.31a16.47 16.47 0 0 1 9.38 3.51A44.8 44.8 0 0 1 43.5 33s-2.8 4.79-10.18 5a47 47 0 0 1-2.86-3.81m6.46-2.9c-3.84 1.945-7.555 3.89-12.92 3.89s-9.08-1.945-12.92-3.89");
}

</style>
