<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="c0o9b701x"/><path class="trsalabnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:candy-crush-soda" /></template>
<style>
.c0o9b701x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.197 33.753q-.656 0-1.334-.025c-3.936-.149-7.006-3.46-6.858-7.396s3.463-7.009 7.395-6.857c5.059.183 8.071-1.337 11.043-3.688a7.131 7.131 0 1 1 8.85 11.184c-3.723 2.947-9.695 6.782-19.096 6.782");
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

.trsalabnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.695 25.898c5.321 0 5.321 2 10.643 2s5.32-2 10.639-2c5.323 0 5.323 2 10.646 2s5.324-2 10.647-2");
}

</style>
