<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7s2f7ifg"/><path class="kvp5c198a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:budget-thuis" /></template>
<style>
.f7s2f7ifg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.671 42.35a2.823 2.823 0 0 0 2.829-2.817V21.216c0-1.139-.89-2.207-1.78-2.915L26.859 7.291C25.177 5.953 25.099 5.65 24 5.65s-1.177.303-2.859 1.64L7.281 18.3c-.892.708-1.781 1.776-1.781 2.915V39.52a2.823 2.823 0 0 0 2.816 2.83z");
}

.kvp5c198a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.758 34.413a4.579 4.579 0 0 1-8.083-2.947v-4.497a4.58 4.58 0 0 1 4.579-4.579a4.57 4.57 0 0 1 3.519 1.65m-9.805 3.518h5.12m-5.12 3.351h5.12");
}

</style>
