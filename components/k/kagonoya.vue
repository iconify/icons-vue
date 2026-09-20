<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sgo2qtd7m"/><path class="j8lhc6bug"/><circle class="cpk0fnbgt"/><path class="pxsqgghvo"/><path class="phgu3fqaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kagonoya" /></template>
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

.j8lhc6bug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.262 39.77A5.5 21.5 0 0 1 18.501 24A5.5 21.5 0 0 1 22 3.972m5.736 4.275C28.821 12.174 29.5 17.767 29.5 24c0 11.874-2.463 21.5-5.5 21.5");
}

.phgu3fqaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.475 36.52A5.5 21.5 45 0 1 20.11 20.111A5.5 21.5 45 0 1 36.52 8.475m2.682.322c2.148 2.148-2.917 10.696-11.313 19.092S10.945 41.351 8.797 39.203M34 5c0 1.933-4.477 3.5-10 3.5c-5.497 0-9.963-1.553-10-3.477m.741 36.655a10 3.5 0 0 1 9.26-2.178a10 3.5 0 0 1 9.258 2.177");
}

.pxsqgghvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203a21.5 5.5 45 0 1-19.092-11.314A21.5 5.5 45 0 1 8.797 8.797m2.683-.322A21.5 5.5 45 0 1 27.889 20.11a21.5 5.5 45 0 1 11.637 16.415");
}

.sgo2qtd7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 3.038-9.626 5.5-21.5 5.5S2.5 27.038 2.5 24m1.648-2.116C7.388 19.897 15.056 18.5 24 18.5c8.981 0 16.676 1.409 19.892 3.41");
}

</style>
