<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ras0s1b_v"/><circle class="qm6uf1bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chacoco-alt" /></template>
<style>
.qm6uf1bwv {
  cx: 24.001px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ras0s1b_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.207 23.692c1.242-2.51-.792-4.797-4.544-5.107s-7.8 1.472-9.043 3.982s.793 4.796 4.545 5.107s7.8-1.473 9.042-3.982m8.198 8.954c1.019-2.661-3.947-7.723-3.947-7.723s-8.904 5.217-9.923 7.877s1.26 4.783 5.09 4.74s7.76-2.234 8.78-4.895M33.681 14.9c-.996 2.388-9.192 6.82-9.192 6.82s-4.398-4.665-3.401-7.053s4.624-4.27 8.101-4.206s5.49 2.052 4.492 4.439m-.071 13.874c-3.245-.32-7.481-5.293-7.481-5.293s8.126-4.395 11.37-4.075c3.245.32 5.004 2.677 3.93 5.264s-4.575 4.424-7.82 4.104");
}

</style>
