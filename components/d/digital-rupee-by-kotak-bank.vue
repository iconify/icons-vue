<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur3p7tbwz"/><path class="o7qpkubjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digital-rupee-by-kotak-bank" /></template>
<style>
.o7qpkubjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.014 17.796a2.25 2.25 0 0 0-4.5 0v1.462a2.25 2.25 0 1 0 4.5 0zm2.532-4.106v6.693c0 .622.503 1.125 1.124 1.125h.338m-2.644-5.962h2.363m6.187 3.712a2.25 2.25 0 0 1-4.5 0v-1.462a2.25 2.25 0 1 1 4.5 0m0 3.712v-5.962m-8.604 18.81a2.25 2.25 0 0 1-1.956 1.136h0a2.25 2.25 0 0 1-2.25-2.251v-1.463a2.25 2.25 0 0 1 2.25-2.25h0a2.25 2.25 0 0 1 2.25 2.25v.731h-4.5m5.829-6.017h1.822c1.666 0 3.017 1.353 3.017 3.023s-1.351 3.023-3.017 3.023l3.017 2.954m-3.017-9h4.142m-5.964 3.038h5.964");
}

.ur3p7tbwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-28.087 7.008v9m0-1.912l4.075-4.054m-2.778 2.764l3.203 3.189m18.174-8.987v9m.001-1.912l4.074-4.054m-2.777 2.764l3.202 3.189");
}

</style>
