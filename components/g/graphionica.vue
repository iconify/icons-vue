<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k3_6mnbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:graphionica" /></template>
<style>
.k3_6mnbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.481 23.195c-2.295-8.662-7.33-15.03-12.29-12.29S10.56 31.562 24.72 44c8.83-9.033 19.195-36.945 11.199-39.685S24 17.42 23.48 23.195");
}

</style>
