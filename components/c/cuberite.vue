<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y32h17ewg"/><path class="nqjli_o-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cuberite" /></template>
<style>
.nqjli_o-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.209 32.132l5.624-2.812v-2.237l-2.236-1.118L9.5 29.014V18.987l12.5 6.25v11.79zM38.5 18.986L26 25.236v11.791l9.791-4.895l-5.624-2.813v-2.236l2.236-1.118l6.097 3.048zM26 10.973v5.86l-2 1l-2-1v-5.86l-9.791 4.895L24 21.764l11.791-5.896z");
}

.y32h17ewg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.5l18.5 9.25v18.5L24 42.5L5.5 33.25v-18.5z");
}

</style>
