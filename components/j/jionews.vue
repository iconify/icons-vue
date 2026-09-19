<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mt27cncxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jionews" /></template>
<style>
.mt27cncxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.705 22.622l-12.846-7.416a1.591 1.591 0 0 0-2.387 1.378v14.832a1.591 1.591 0 0 0 2.387 1.378l12.846-7.416a1.591 1.591 0 0 0 0-2.756m-20.419 6.256H5.5m15.786-9.756H5.5m15.786-9.755H5.5m15.786 29.266H5.5");
}

</style>
