<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v74vy5bdz"/><path class="s_7evzb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mail-com" /></template>
<style>
.s_7evzb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.285 41.741L8.878 35.02a3 3 0 0 1-2.372-2.933V8a2 2 0 0 1 2-2h28.988a4 4 0 0 1 4 4v30.763a1 1 0 0 1-1.21.978");
}

.v74vy5bdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.925 18.103a6.038 6.038 0 0 1 12.075 0v9.962m-12.075-16v16M24 18.103a6.038 6.038 0 0 1 12.075 0v9.962");
}

</style>
