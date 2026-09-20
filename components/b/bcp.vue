<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="gcmscz5xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bcp" /></template>
<style>
.gcmscz5xl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.639 20.406zc2.636 1.974-1.328 5.86-2.762 5.928c0 0 .627 1.152 1.596 1.221s3.875-2.691 4.227-3.813s-3.061-3.337-3.061-3.337c-1.519.142-1.798 1.508-1.855 1.63c1.167.334 1.723.972 2.341 1.498m-19.893.486a1.783 1.783 0 1 1 0 3.565H15.29v-7.131h2.942a1.783 1.783 0 1 1 0 3.565m0 .001H15.29m11.627 1.174v.029a2.362 2.362 0 1 1-4.725 0v-2.407a2.362 2.362 0 1 1 4.725 0v.03m2.177 4.739v-7.131h2.335c1.32 0 2.39 1.072 2.39 2.395s-1.07 2.395-2.39 2.395h-2.335m-19.062-4.837zc2.636 1.974-1.328 5.86-2.763 5.928c0 0 .628 1.152 1.597 1.221c.97.07 3.875-2.691 4.227-3.813s-3.061-3.337-3.061-3.337c-1.519.142-1.798 1.508-1.855 1.63c1.167.334 1.723.972 2.341 1.498");
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
