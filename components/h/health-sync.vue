<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ktio-1b-w"/><path class="t82f-75ay"/><circle class="b9-t7yv9e"/><path class="bzx48gbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:health-sync" /></template>
<style>
.b9-t7yv9e {
  cx: 25.311px;
  cy: 12.199px;
  r: 2.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bzx48gbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.703 30.222l-2.919 3.555c-1.398 1.618.62 3.037 2.1 1.637l2.859-3.602l.938-3.52L24.19 29.8l1.006 5.207c.665 1.449 2.828 1.37 2.757-.494l-1.49-5.564l-2.137-3.7l1.197-4.465l1.335.358a.78.78 0 0 0 .387.772c.465.248 3.808 1.272 3.808 1.272c2.103.646 2.34-1.471.64-1.964l-2.783-.747l-1.378-2.294l-2.239-2.006l-3.423-.08l-4.838 2.921l-1.797 4.802c-.397 1.342 1.527 1.691 2.059.648c.258-.458 1.558-3.552 1.558-3.552l2.824-1.402l-1.381 6.334Z");
}

.ktio-1b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.98 41.875a20.484 20.484 0 1 1 18.21-.083");
}

.t82f-75ay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.816 38.606l-1.99 4.364L34.072 45");
}

</style>
