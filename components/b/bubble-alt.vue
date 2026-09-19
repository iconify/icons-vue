<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c0ad3vmwl"/><path class="vvbu7jhda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bubble-alt" /></template>
<style>
.c0ad3vmwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.152 5.5L42.5 34.847L34.846 42.5L5.5 13.153z");
}

.vvbu7jhda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.2 16.546a3.9 3.9 0 0 0-1.043.745c-1.771 1.771-1.517 4.898.569 6.983s5.212 2.34 6.983.569a3.9 3.9 0 0 0 .745-1.042m-16.412-1.105l7.653-7.653m2.609 17.915l7.653-7.653");
}

</style>
