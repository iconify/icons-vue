<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjrro1bxo"/><path class="g6k3p2dzf"/><path class="u7oy0tboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cattorrent" /></template>
<style>
.g6k3p2dzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.75 25.623l5.499 1.436l6.067 1.354l-5.375 2.46zm13.188 10.862h4.217v.703l-1.705 2.118l-.962-.03l-1.55-2.088zm-1.622-20.691l2.397 2.284l4 3.834l5.116 4.734l5.643-1.385l-2.925 4.3l4.02 3.896");
}

.sjrro1bxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.334 42.5l4.186-.02l4.909-.114l12.35-10.45l.207-26.23l-11.059 10.005l-11.947-.052L7.128 5.5l-.01 5.85l2.046 2.925l-2.046-.424l-.104 17.983z");
}

.u7oy0tboj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.829 26.646l-1.457.34l-3.824 1.003l5.601 3.525l1.613-1.25l.785-.704m-21.301-2.48l1.571 3.1l1.705-2.439");
}

</style>
