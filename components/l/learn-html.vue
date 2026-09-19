<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="e712uubjt"/><path class="g1zhw3tqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:learn-html" /></template>
<style>
.e712uubjt {
  d: path("M30.7 23.7H17.3l.5 7.3h12.6l-.6 7.9l-5.8 1.6l-5.7-1.6l-.2-3.3");
}

.g1zhw3tqy {
  stroke-miterlimit: 10;
  d: path("M36.4 7.5v9.9h5m-17.1-.1V7.5l4.9 9.9l4.9-9.9v9.9M15.5 7.5H22m-3.3 9.9V7.5m-12.1 0v9.9m6.6-9.9v9.9m-6.6-5h6.6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
