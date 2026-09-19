<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2ss5yb2b"/><path class="gu-7p9bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:creditagricole" /></template>
<style>
.d2ss5yb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.97 37.07h38.06M19.91 12.38C10.85 13.5 4.5 16.82 4.5 24c0 4.38 4.51 6.53 8.66 6.53c8.61 0 21.7-8.31 30.34-13.18");
}

.gu-7p9bfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.98 25.23l6.89-12.85l9.91 19.04m6.72-20.49a86 86 0 0 1-9.1 5.12");
}

</style>
