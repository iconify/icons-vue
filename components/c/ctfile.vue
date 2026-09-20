<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iclvc8r4e"/><path class="wc2j6gbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ctfile" /></template>
<style>
.iclvc8r4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.192 18.508a11.824 11.824 0 0 1 23.28 0m-13.343 9.079l-1.413-2.116A8.853 8.853 0 0 0 4.5 30.389a8.854 8.854 0 0 0 8.853 8.854h21.294");
}

.wc2j6gbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.46 21.614a8.855 8.855 0 0 1 10.04 8.775a8.854 8.854 0 0 1-16.216 4.918l-1.338-2.004");
}

</style>
