<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1hgylbly"/><circle class="i72x8cveu"/><circle class="t8lmq_bjw"/><circle class="as8y7jboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esa-impact" /></template>
<style>
.as8y7jboh {
  cx: 26.311px;
  cy: 35.932px;
  r: 2.144px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i72x8cveu {
  cx: 32.607px;
  cy: 19.844px;
  r: 7.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n1hgylbly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.794 42.181A21.55 21.55 0 0 0 24 45.299c11.874 0 21.5-9.536 21.5-21.299S35.874 2.7 24 2.7S2.5 12.238 2.5 24c0 3.573.888 6.94 2.458 9.898c0 0 5.4-1.036 7.122 2.615c1.722 3.65.714 5.668.714 5.668");
}

.t8lmq_bjw {
  cx: 13.111px;
  cy: 19.587px;
  r: 3.865px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
