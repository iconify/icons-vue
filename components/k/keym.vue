<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly3ymsy4p"/><path class="nkt5f4b2l"/><path class="nljp2qb3l"/><path class="z6mjbmb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keym" /></template>
<style>
.ly3ymsy4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.554 5.5v37m6.633-37L9.73 24l4.457 18.5");
}

.nkt5f4b2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.669 5.5L12.784 24l8.886 18.5");
}

.nljp2qb3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.276 5.5L16.656 24l13.62 18.5");
}

.z6mjbmb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.446 5.5L21.946 24l18.5 18.5");
}

</style>
