<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_jf7mnwu"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gls-banking" /></template>
<style>
.i_jf7mnwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.323 22.117a3.895 3.895 0 0 0-3.878-3.912h-.033a3.895 3.895 0 0 0-3.912 3.878v3.945c0 2.174 1.739 3.767 3.912 3.767s3.911-1.739 3.911-3.767h-3.911m15.554 2.463c.725.87 1.593 1.304 2.897 1.304h1.74a2.906 2.906 0 0 0 2.897-2.897A2.906 2.906 0 0 0 34.602 24H32.72a2.906 2.906 0 0 1-2.898-2.898a2.906 2.906 0 0 1 2.898-2.897h1.739c1.303 0 2.173.29 2.896 1.304m-15.742-1.304v11.59h5.795");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
