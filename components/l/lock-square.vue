<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_ugecb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lock-square" /></template>
<style>
.z_ugecb3o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25m3.125 8.5h3V10q0-1.5-1.5-1.5T10.5 10zm4.5.067V10q0-3-3-3t-3 3v.817q-1.75.341-1.75 2.433v2.5q0 2.5 2.5 2.5h4.5q2.5 0 2.5-2.5v-2.5q0-2.092-1.75-2.433");
}

</style>
