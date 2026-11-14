<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir3jxcp5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cup-name-label" /></template>
<style>
.ir3jxcp5f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 2.25h12.5q2.5 0 2.5 2.5q0 1.623-1.054 2.193l-1.953 14.159q-.009.067-.03.131t-.053.124t-.074.112t-.093.096q-.051.045-.109.079q-.058.035-.121.058q-.063.024-.129.036q-.067.012-.134.012H7q-.067 0-.134-.012q-.066-.012-.129-.036t-.121-.058t-.109-.079t-.093-.096q-.042-.053-.074-.112t-.053-.124t-.03-.131L4.304 6.943Q3.25 6.373 3.25 4.75q0-2.5 2.5-2.5m.111 5l1.793 13h8.692l1.793-13zm4.889 2h2.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T8.25 13.25v-1.5q0-2.5 2.5-2.5");
}

</style>
