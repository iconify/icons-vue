<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ivdwqlban"/><circle class="wu5gqkbyh"/><path class="qkycmqbng"/><path class="v2ja4p65h"/><path class="cee6ppe7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calmac-ferries" /></template>
<style>
.cee6ppe7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.957 22.48c1.495.836 3.775.509 3.775.509L24 24.684s-1.064-.101-.786 1.343s.355 1.977.355 1.977l-1.115.456s-.836-1.317-1.749-.557");
}

.ivdwqlban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 9.352H12.292L5.5 38.648h30.208z");
}

.qkycmqbng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.345 18.4c2.89 2.382-.135 2.736-.135 4.08s1.833 2.432.313 3.218m-5.525-4.891s-1.647.152-2.661-1.52");
}

.v2ja4p65h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.343 30.386c1.445-.202 1.377-1.334 1.377-1.334c.803-.932 1.335-1.808 1.335-1.808l-1.04-1.546l-1.85-2.534c1.065-4.511-.109-7.062-2.846-5.314");
}

.wu5gqkbyh {
  cx: 24px;
  cy: 24px;
  r: 9.275px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
