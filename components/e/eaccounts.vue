<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k2tfzqbdi"/><path class="zaurhqdow"/><path class="o67wl1brq"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eaccounts" /></template>
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

.k2tfzqbdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.712 26.853v-2.5c0-.588.319-1.129.833-1.415a1.62 1.62 0 0 1 1.642.044l8.354 5.223c.472.292.755.808.755 1.36s-.283 1.07-.755 1.362l-8.338 5.213a1.63 1.63 0 0 1-1.652.044a1.63 1.63 0 0 1-.839-1.424v-2.488");
}

.o67wl1brq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.288 15.728h8.693a2.69 2.69 0 0 1 2.691 2.69v.003a2.725 2.725 0 0 1-2.727 2.728h-8.657");
}

.zaurhqdow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.712 32.272H8.02a2.69 2.69 0 0 1-2.691-2.69v-.003a2.725 2.725 0 0 1 2.728-2.728h8.656m14.575-5.703v2.5a1.62 1.62 0 0 1-.832 1.414a1.62 1.62 0 0 1-1.643-.044l-8.354-5.222c-.471-.293-.754-.809-.754-1.362s.283-1.068.754-1.361l8.338-5.213a1.63 1.63 0 0 1 1.652-.044c.517.288.84.834.84 1.424v2.488");
}

</style>
