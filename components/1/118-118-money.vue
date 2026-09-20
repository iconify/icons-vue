<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="u0cqbut4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:118-118-money" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.u0cqbut4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.784 12.955l2.672-1.455v10.688m5.553-5.344a2.672 2.672 0 0 0 0 5.344h1.737a2.672 2.672 0 0 0 0-5.344m0 0a2.672 2.672 0 0 0 0-5.344h-1.737a2.672 2.672 0 0 0 0 5.344m0 0h1.737m8.061 0a2.672 2.672 0 0 0 0 5.344h1.737a2.672 2.672 0 0 0 0-5.344m0 0a2.672 2.672 0 0 0 0-5.344h-1.737a2.672 2.672 0 0 0 0 5.344m0 0h1.737m-19.76 10.423l2.672-1.455V36.5m5.553-5.344a2.672 2.672 0 0 0 0 5.344h1.737a2.672 2.672 0 0 0 0-5.344m0 0a2.672 2.672 0 0 0 0-5.344h-1.737a2.672 2.672 0 0 0 0 5.344m0 0h1.737m8.061 0a2.672 2.672 0 0 0 0 5.344h1.737a2.672 2.672 0 0 0 0-5.344m0 0a2.672 2.672 0 0 0 0-5.344h-1.737a2.672 2.672 0 0 0 0 5.344m0 0h1.737");
}

</style>
