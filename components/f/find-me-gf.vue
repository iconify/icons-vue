<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxn-a3dvm"/><path class="q643hbc2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:find-me-gf" /></template>
<style>
.q643hbc2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.348 15.978a4.02 4.02 0 0 0-4.23-4.017c-2.17.114-3.798 2.066-3.798 4.244v3.728a4.02 4.02 0 0 0 4.014 4.022a4.02 4.02 0 0 0 4.014-4.022h-4.014m7.346-7.978h6m-6 6h3.9m-3.9-6v12");
}

.yxn-a3dvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.502c-7.23 0-13.09 5.86-13.09 13.09c0 10.25 10 22.61 12.61 25.63a.8.8 0 0 0 1.21 0c2.55-3 12.36-15.38 12.36-25.63c0-7.23-5.86-13.09-13.09-13.09");
}

</style>
