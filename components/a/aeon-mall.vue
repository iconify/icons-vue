<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bj0srk4ed"/><path class="aplo1o7mj"/><path class="fbzhawb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aeon-mall" /></template>
<style>
.aplo1o7mj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 22.186l5.642-7.338h5.542m9.767 3.669c0 2.214-2.092 4.008-4.673 4.008h-.001c-2.581 0-4.674-1.794-4.674-4.008s2.093-4.008 4.674-4.008c2.58 0 4.673 1.794 4.674 4.007z");
}

.bj0srk4ed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.463 18.51c-.003.622-2.947 1.126-6.576 1.125c-3.632 0-6.576-.504-6.576-1.126c.003-.622 2.946-1.125 6.576-1.125c3.631 0 6.576.504 6.576 1.126");
}

.fbzhawb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.684 14.848h-4.347v7.338h4.347m11.636-.02v-7.298l6.18 7.298v-7.298M27.677 26.174v7.318h3.659m2.505-7.338v7.318H37.5m-27 .012v-7.31l3.659 7.318l3.659-7.306v7.306m6.55-2.424h-3.242m-.803 2.424l2.424-7.317l2.424 7.317");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
