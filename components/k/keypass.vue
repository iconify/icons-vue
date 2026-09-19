<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zp_7hvbav"/><path class="hfc7bsbjg"/><path class="s6fjx5bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keypass" /></template>
<style>
.hfc7bsbjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.778 18.868h13.756v7.527c0 3.225-3.636 6.842-6.878 6.842s-6.878-3.617-6.878-6.842Zm6.878 4.79v3.474");
}

.s6fjx5bjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.842 18.868v-2.79a5.4 5.4 0 0 1 4.814-4.788a5.4 5.4 0 0 1 4.815 4.79v2.79");
}

.zp_7hvbav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.462 6.553h4.814L14.027 4.5h19.258l2.751 2.053h5.502V22.29c0 15.731-17.882 21.21-17.882 21.21S6.462 38.066 6.462 22.29Z");
}

</style>
