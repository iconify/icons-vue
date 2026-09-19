<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oou6-6bhr"/><path class="p9-63zb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anidroid" /></template>
<style>
.oou6-6bhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.785 7.099c-3.336-1.901-7.026-4.668-7.205-.167a9.86 9.86 0 0 0 .333 4.998c-2.735 6.426-2.029 10.916-1.832 31.569h8.496v-9.662c1.832-3.725 4.924-6.026 8.829-5.54V43.5h8.58c.182-11.306.753-30.34-2.333-32.11c.836-8.285.843-8.026-6.747-4.248c-2.415-1.925-4.81-1.565-8.121-.042");
}

.p9-63zb2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.618 23.175a10.85 10.85 0 0 1 8.538-3.707c1.356-4.823-7.88-9.286-8.538.333Z");
}

</style>
