<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><g class="y9tr6bcfx"><path class="ac0qmfbto"/><path class="q8z3lbcjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bigbasket" /></template>
<style>
.ac0qmfbto {
  d: path("M11.723 11.639v24.75m15.349-8.279c.01 4.414-3.397 8.006-7.62 8.033s-7.673-3.521-7.713-7.936c-.041-4.414 3.342-8.031 7.565-8.09S27 23.582 27.07 27.996M20.838 11.61v7.163");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.q8z3lbcjb {
  d: path("M25.613 20.953c3.284-1.377 6.996-.466 9.098 2.233c2.102 2.698 2.087 6.532-.039 9.396c-2.125 2.864-5.845 4.066-9.119 2.946");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
