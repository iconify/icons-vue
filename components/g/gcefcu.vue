<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kmkm8rb6q"/><circle class="qr2izdbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gcefcu" /></template>
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

.kmkm8rb6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.819 18.397c1.056 2.542 4.755 4.449 6.604 6.038s1.85 2.86 1.85 4.13c1.585-3.177 3.17-6.355 2.113-8.897s-4.755-4.448-6.605-6.037s-1.85-2.86-1.85-4.131c-1.584 3.178-3.17 6.355-2.112 8.897m-6.205 10.029c1.057 2.519 4.756 4.407 6.605 5.981s1.85 2.834 1.85 4.093c1.584-3.148 3.17-6.296 2.113-8.815s-4.756-4.407-6.605-5.981s-1.85-2.834-1.85-4.093c-1.584 3.148-3.17 6.296-2.113 8.815");
}

.qr2izdbms {
  cx: 24px;
  cy: 24px;
  r: 18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
