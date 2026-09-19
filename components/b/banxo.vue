<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zz9h_fbum"/><circle class="fsvnzcb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banxo" /></template>
<style>
.fsvnzcb7b {
  cx: 35.178px;
  cy: 25.34px;
  r: 0.75px;
  fill: currentColor;
}

.zz9h_fbum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.709 27.988h12.813M26.157 42.5h14.807m-10.362-6.799h7.404M12.2 18.836h12.813M9.455 23.412h12.813m15.035-2.615l3.988 4.51l-2.746 2.681M38.61 5.5c-15.492 7.06-37.457 21.376-19.48 37l15.1-25.756");
}

</style>
