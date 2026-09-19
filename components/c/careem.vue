<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_sr_5beu"/><path class="moqc0136m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:careem" /></template>
<style>
.moqc0136m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M28.936 4.6a19.9 19.9 0 0 1 12.474 8.819m1.484 18.319a19.886 19.886 0 0 1-37.787-3.706");
}

.w_sr_5beu {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M12.652 4.328a4.68 4.68 0 0 1 5.567 2.436a4.73 4.73 0 0 1-.488 4.872a4.74 4.74 0 0 1-5.707 1.322a4.67 4.67 0 0 1-2.504-3.2a4.48 4.48 0 0 1 .417-3.133a4.9 4.9 0 0 1 2.715-2.297Z");
}

</style>
