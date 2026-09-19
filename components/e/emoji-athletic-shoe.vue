<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bntmuebrb"/><path class="og99-hbge"/><path class="d6ktfpbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-athletic-shoe" /></template>
<style>
.bntmuebrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.27 30.98c-1.327-1.087-1.77-4.844-1.77-6.688c0-1.637.667-6.053 1.745-7.126c0 0 1.568-.665 2.383 0c2.67 2.177 8.054 7.168 14.746 0c0 0 10.366 4.896 13.162 5.602c4.802 1.213 4.964 2.418 4.964 4.004c0 5.077-5.947 4.424-9.913 4.208c-2.187-.118-22.883.133-25.318 0");
}

.d6ktfpbou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.27 30.98c-1.327-1.087-1.77-4.844-1.77-6.688c0-1.637.667-6.053 1.745-7.126c0 0 1.568-.665 2.383 0c2.67 2.177 8.054 7.168 14.746 0c0 0 10.366 4.896 13.162 5.602c4.802 1.213 4.964 2.418 4.964 4.004c0 5.077-5.947 4.424-9.913 4.208c-2.187-.118-22.883.133-25.318 0m19.721-9.45L24 25.016m5.99-2.428l-2.084 2.427");
}

.og99-hbge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.859 27.903s8.925-1.444 14.446.065s16.716.721 16.716.721");
}

</style>
