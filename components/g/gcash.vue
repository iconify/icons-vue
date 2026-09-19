<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bd8ttnbub"/><path class="ku05oj2yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gcash" /></template>
<style>
.bd8ttnbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.824 33.23a16.12 16.12 0 0 0-.01-18.475m-1.806-2.149a16.114 16.114 0 1 0 0 22.788");
}

.ku05oj2yj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.461 16.923A9.18 9.18 0 1 0 29.794 24h-8.066m17.648 13.109a22.9 22.9 0 0 0-.015-26.24");
}

</style>
