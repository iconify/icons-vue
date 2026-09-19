<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fo_thubga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ebbanking" /></template>
<style>
.fo_thubga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h8.333v12.333H5.5V9.5c0-2.208 1.792-4 4-4m8.333 0h12.333v12.333H17.833zm12.334 0H38.5c2.208 0 4 1.792 4 4v8.333H30.167zM5.5 17.833h12.333v12.333H5.5zm24.667 0H42.5v12.333H30.167zM5.5 30.167h12.333V42.5H9.5c-2.208 0-4-1.792-4-4zm12.333 0h12.333V42.5H17.833zm12.334 0H42.5V38.5c0 2.208-1.792 4-4 4h-8.333z");
}

</style>
