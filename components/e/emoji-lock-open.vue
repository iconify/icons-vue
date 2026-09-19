<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nu00wacyl"/><circle class="n0zj0mbta"/><path class="e1n9j0ncc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-lock-open" /></template>
<style>
.e1n9j0ncc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.522 22.793h28.956V42.5H9.522z");
}

.n0zj0mbta {
  cx: 24px;
  cy: 32.647px;
  r: 3.016px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nu00wacyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.348 15.152c0-5.33 4.321-9.652 9.652-9.652s9.652 4.321 9.652 9.652v7.641");
}

</style>
