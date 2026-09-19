<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1dei5bih"/><path class="n50ykac5i"/><circle class="l1dutkqjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drinkable" /></template>
<style>
.l1dutkqjb {
  cx: 32.345px;
  cy: 7.676px;
  r: 1.887px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n50ykac5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 18.338s2.422-.734 3.67-.734s2.421.734 3.669.734s2.422-.734 3.67-.734s2.421.734 3.669.734s2.421-.754 3.67-.734c.552.009 1.614.377 1.614.377m-6.962-.167l4.273-8.412m1.751-3.446l.74-1.456");
}

.u1dei5bih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.758 43.5h10.484M24 43.5V28.822L9.322 13.62h29.356L24 28.822");
}

</style>
