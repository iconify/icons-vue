<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzmtopq2o"/><path class="vqng1ouao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chronal" /></template>
<style>
.hzmtopq2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.44 31.421V16.58a4.59 4.59 0 0 0-2.293-3.972l-12.854-7.42a4.59 4.59 0 0 0-4.586 0l-12.854 7.42A4.59 4.59 0 0 0 6.56 16.58v14.84c0 1.638.874 3.152 2.293 3.971l12.854 7.422a4.59 4.59 0 0 0 4.586 0l12.854-7.422a4.59 4.59 0 0 0 2.293-3.97");
}

.vqng1ouao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.905 20.19L25.753 5.255a2.415 2.415 0 0 0-3.506 0L8.095 20.19a5.54 5.54 0 0 0 0 7.618l14.152 14.937a2.415 2.415 0 0 0 3.506 0l14.152-14.937a5.54 5.54 0 0 0 0-7.618M24 33.686V14.314m3.8 16.543V17.143M31.599 28v-8m3.8 5.143v-2.286M20.2 17.143v13.714M16.401 20v8m-3.8-5.143v2.286");
}

</style>
