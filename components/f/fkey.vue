<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ozus40m6l"/><path class="rzan5tt4c"/><path class="f608ibc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fkey" /></template>
<style>
.f608ibc5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 41.136h19.948l3.916-6.784l-2.76-4.779l-3.913 6.78h-9.107l1.855-3.212l-2.711-4.695z");
}

.ozus40m6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.336 6.865L12.362 24.14l3.917 6.783h5.518l-3.915-6.78l4.553-7.886l1.855 3.212h5.422z");
}

.rzan5tt4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 39.015L33.526 21.74h-7.833l-2.759 4.779h7.829l4.553 7.886h-3.708l-2.711 4.696z");
}

</style>
