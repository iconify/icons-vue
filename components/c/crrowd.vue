<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hamrq5b7i"/><path class="e5o1ud2fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crrowd" /></template>
<style>
.e5o1ud2fq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.88 15.348h.012a6.97 6.97 0 0 0-5.896-3.258h0a6.943 6.943 0 1 0 5.899 10.629h-.015");
}

.hamrq5b7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.434 37.44a3.008 3.008 0 1 0 0 6.016h23.133a3.008 3.008 0 1 0 0-6.016Zm17.742 6.06v-5.762m-.296-22.39h8.216a14.532 14.532 0 1 0 0 7.371H29.88");
}

</style>
