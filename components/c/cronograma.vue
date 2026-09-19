<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="an_ja9p-f"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cronograma" /></template>
<style>
.an_ja9p-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 14.21h25m-25 6.53h4.28m-4.28 6.52h4.28m-4.28 6.53h4.28m17.46-13.05h3.26m-4.28 6.52h4.28m-4.28 6.53h4.28m-15.99 0h6.98m-7.83-10.86L24 27.26l6.67-6.66");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
