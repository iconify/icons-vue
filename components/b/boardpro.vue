<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rf6lnmp1x"/><path class="k61_v2b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boardpro" /></template>
<style>
.k61_v2b4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.213 15.804l-14.426-7.93L22.945 4.5l14.426 7.93v6.749l-14.426 7.93l-6.158-3.375z");
}

.rf6lnmp1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.629 36.751V11.249l6.158-3.375v32.252zm20.584-4.555l-14.426 7.93l6.158 3.374l14.426-7.93v-9.624l-6.158-3.374z");
}

</style>
