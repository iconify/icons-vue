<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kelym6ltg"/><path class="f1ffhfq9j"/><path class="qp_sr1bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dsdrive" /></template>
<style>
.f1ffhfq9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.9 41.11a2.77 2.77 0 0 0 2.41 1.39h18.14a2.8 2.8 0 0 0 2.42-1.39l9.07-15.72a2.76 2.76 0 0 0 0-2.78L32.87 6.89a2.8 2.8 0 0 0-2.42-1.39H12.31A2.77 2.77 0 0 0 9.9 6.89l-4.21 7.29l4.86 8.43a2.76 2.76 0 0 1 0 2.78l-4.86 8.43Z");
}

.kelym6ltg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.42 41.74a2.7 2.7 0 0 0 .52-.63L20 25.39a2.76 2.76 0 0 0 0-2.78L10.94 6.89a2.7 2.7 0 0 0-.52-.63");
}

.qp_sr1bfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.65 23.3l-4.53-7.85a1.39 1.39 0 0 0-1.21-.69h-9.06a1.39 1.39 0 0 0-1.07.52L20 22.61a2.76 2.76 0 0 1 0 2.78l-4.23 7.33a1.39 1.39 0 0 0 1.07.52h9.06a1.39 1.39 0 0 0 1.21-.69l4.53-7.85a1.4 1.4 0 0 0 .01-1.4");
}

</style>
