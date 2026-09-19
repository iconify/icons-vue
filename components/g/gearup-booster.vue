<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lcuskcbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gearup-booster" /></template>
<style>
.lcuskcbni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.908 18.86L37.125 5.5l.033 35.796l-4.511-23.51zm1.659 8.99L36.54 42.5L5.32 24.499l24.312 6.962zm-8.557-3.134l-16.168-1.28L35.824 5.5L17.877 22.98z");
}

</style>
