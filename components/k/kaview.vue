<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zg9eunb2b"/><path class="kv8w8tbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kaview" /></template>
<style>
.kv8w8tbyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 13.319H9.611l4.11 7.12m4.112 7.121l8.222 14.241L42.5 13.318h-8.222");
}

.zg9eunb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 20.44h-8.222l4.11 7.12l8.223-14.24h-8.222l-4.111-7.121L5.5 34.682h8.222l8.222-14.241");
}

</style>
