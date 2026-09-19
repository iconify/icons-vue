<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4elcneoe"/><path class="cy0nuushk"/><rect class="pb70797nl"/><path class="hw_15ebbo"/><rect class="o2_c0d08b"/><path class="i0w7k5b6q"/><rect transform="matrix(-1 0 0 -1 62.9 13.362)" class="oktadutgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:k9mail" /></template>
<style>
.cy0nuushk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.187 31.24l4.416 6.553a2.61 2.61 0 0 0 2.276 1.301h2.179m7.884 0h2.169a2.61 2.61 0 0 0 2.276-1.3l4.426-6.555");
}

.hw_15ebbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.906 11.143V8.862");
}

.i0w7k5b6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.094 11.143V8.862");
}

.o2_c0d08b {
  width: 7.855px;
  height: 4.362px;
  x: 12.622px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
}

.oktadutgb {
  width: 7.855px;
  height: 4.362px;
  x: 27.523px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
}

.pb70797nl {
  width: 33.195px;
  height: 20.096px;
  x: 7.402px;
  y: 11.143px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
}

.y4elcneoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.942 35.91a1.97 1.97 0 0 0-1.97-1.97h-3.943a1.97 1.97 0 0 0-1.971 1.971v3.647a3.942 3.942 0 1 0 7.884 0Zm9.679-22.096L24 22.369l-13.621-8.555");
}

</style>
