<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-frx9b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:houzz" /></template>
<style>
.o-frx9b2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.423 5.5v37H19.86V30.845h8.282V42.5h12.436V21.487l-24.904-7.122V5.5z");
}

</style>
