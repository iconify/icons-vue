<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="car9wqb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:border-fence" /></template>
<style>
.car9wqb9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19m3.75 0V11l1.5-1.5l1.5 1.5v10.5m2.75 0V11L14 9.5l1.5 1.5v10.5m2.75 0V11l1.5-1.5l1.5 1.5v10.5M3 15h3.75m3 0h2.75m3 0h2.75M5.005 3.216L6.5 3.75a1.327 1.327 0 0 1 0 2.5l-1.495.534A1.5 1.5 0 0 1 3 5.371v-.742a1.5 1.5 0 0 1 2.005-1.413");
}

</style>
