<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k1n6tobwb"/><path class="go64vhinp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jinovel" /></template>
<style>
.go64vhinp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.284 28.884c-1.543-.615-1.392.789-.444 3.161c.822.015 2.094.126 2.543-.526c1.566-2.272-.565-4.938-1.985-5.267c-4.8-1.114-3.821 4.22-1.837 6.976c3.636 5.052 8.336 8.663 14.145 9.135c4.708.382 7.401-.073 12.134-.839c2.032-.329 4.275-1.342 8.235-1.17");
}

.k1n6tobwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.635 5.5l2.776 3.044M13.903 27.111l-2.759-3.06m0 0L31.635 5.5l-3.372.183L7.771 24.236zm2.759 3.06L34.41 8.544l.002 3.24l-20.51 18.569z");
}

</style>
