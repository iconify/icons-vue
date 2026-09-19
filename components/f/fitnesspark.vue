<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j-s1ul2hz"/><path class="xogd_8hmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fitnesspark" /></template>
<style>
.j-s1ul2hz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.791 8.531c9.642 1.561 23.859 12.716 11.405 32.97");
}

.xogd_8hmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.348 41.5c4.567-4.404 7.22-8.721 7.22-14.223c0-6.62-3.385-12.257-10.89-12.257c-4.95 0-7.178 2.557-7.178 5.736c0 4.26 3.425 5.473 5.538 5.473c3.048 0 4.064-3.016 4.064-3.016M32.8 41.5c4.456-11.339 6.967-21.015-6.162-35m13.109 35c4.14-12.06 3.411-21.046-.852-29.101");
}

</style>
