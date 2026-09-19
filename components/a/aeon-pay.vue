<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="l8k9nbr4r"/><path class="aplo1o7mj"/><path class="d2nwrabyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aeon-pay" /></template>
<style>
.aplo1o7mj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 22.186l5.642-7.338h5.542m9.767 3.669c0 2.214-2.092 4.008-4.673 4.008h-.001c-2.581 0-4.674-1.794-4.674-4.008s2.093-4.008 4.674-4.008c2.58 0 4.673 1.794 4.674 4.007z");
}

.d2nwrabyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.684 14.848h-4.347v7.338h4.347m11.636-.02v-7.298l6.18 7.298v-7.298");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.l8k9nbr4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.388 33.46v-7.285h2.385a2.444 2.444 0 0 1 2.442 2.446a2.444 2.444 0 0 1-2.442 2.447h-2.385m10.469.571a1.821 1.821 0 0 1-3.643 0v-1.184a1.821 1.821 0 0 1 3.643 0m0 3.005v-4.827m3.94 2.368l-1.94-4.826m3.643-.001l-2.313 6.556c-.154.437-.567.73-1.03.73h-.3m-7.394-14.95c-.003.622-2.947 1.126-6.576 1.125c-3.632 0-6.576-.504-6.576-1.126c.003-.622 2.946-1.125 6.576-1.125c3.631 0 6.576.504 6.576 1.126");
}

</style>
