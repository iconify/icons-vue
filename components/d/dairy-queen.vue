<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1lmivb7d"/><path class="lmfqi5h1o"/><path class="k83ytvbuj"/><rect class="vlr9anbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dairy-queen" /></template>
<style>
.k83ytvbuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.016 32.729c-6.958 4.722-15.532 3.293-23.546 0l1.337-4.457c5.3 3.298 8.23 5.762 22.21 4.457m-13.15-4.249v-9.466h2.13a4.14 4.14 0 0 1 4.142 4.142v1.183a4.14 4.14 0 0 1-4.142 4.142zm15.046.001l-3.136-3.099");
}

.lmfqi5h1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.529 12.278c-1.562-.543-3.38-.864-5.529-.864c-12.043 0-13.473 10.004-19.5 12.586c2.692 1.152 4.465 3.767 6.659 6.326c0 0 0 .011.01.011m7.302 5.385c1.562.543 3.38.864 5.529.864c12.044 0 13.473-10.004 19.5-12.586c-2.692-1.152-4.465-3.767-6.659-6.326l-.01-.011");
}

.u1lmivb7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.984 15.271c6.958-4.722 15.532-3.293 23.547 0l-1.338 4.457c-5.3-3.298-8.23-5.762-22.21-4.457");
}

.vlr9anbgk {
  width: 6.272px;
  height: 9.467px;
  x: 25.641px;
  y: 19.014px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.136px;
  ry: 3.136px;
}

</style>
