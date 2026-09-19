<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9-9-acei"/><rect class="r-w2wj7ys"/><path class="tg28p2ioi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keycip" /></template>
<style>
.r-w2wj7ys {
  width: 32.457px;
  height: 22.024px;
  x: 7.771px;
  y: 20.476px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.012px;
}

.tg28p2ioi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.316 20.476c-.403-20.261 25.103-19.672 24.717 0M17.625 36.695h12.751v2.898H17.625zm-5.043-11.868h2.898v2.898h-2.898z");
}

.w9-9-acei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.567 24.827h2.898v2.898h-2.898zm4.984 0h2.898v2.898h-2.898zm4.984 0h2.898v2.898h-2.898zm4.985 0h2.898v2.898H32.52zm-19.938 4.984h2.898v2.898h-2.898zm4.985 0h2.898v2.898h-2.898zm4.984 0h2.898v2.898h-2.898zm4.984 0h2.898v2.898h-2.898zm4.985 0h2.898v2.898H32.52z");
}

</style>
