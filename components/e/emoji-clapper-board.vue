<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="upltr6shm"/><path class="twqlhsb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clapper-board" /></template>
<style>
.twqlhsb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.687 11.079l-5.886-3.034l3.361-1.291l4.615 2.378M13.02 26.69h3.601l4.405-4.943h-3.6zm9.227 0h3.6l4.406-4.943h-3.6zm9.227 0h3.6l4.405-4.943h-3.6zm-2.252-13.515l-3.362 1.289l-5.883-3.038l3.362-1.289zm-8.505 3.275l-3.37 1.265l-5.863-3.079l3.371-1.265zm-10.089 9.972v-2.375m-2.538-2.3a1.93 1.93 0 0 0 3.862.002v-.002a1.93 1.93 0 0 0-3.862-.002z");
}

.upltr6shm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.628 26.69v13.504a2.306 2.306 0 0 0 2.307 2.306H38.24a2.306 2.306 0 0 0 2.307-2.305V26.69zm.887-6.728l25.64-9.849L35.38 5.5L7.452 16.228l1.336 3.475m3.615 2.044h28.145v4.943");
}

</style>
