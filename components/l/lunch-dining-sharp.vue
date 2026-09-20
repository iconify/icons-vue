<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbck4sluk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lunch-dining-sharp" /></template>
<style>
.hbck4sluk {
  fill: currentColor;
  d: path("M3 20v-4.384h18V20zm7.642-6.884q-.476.5-1.646.5t-1.64-.5t-1.352-.5t-1.358.5q-.477.5-1.646.5v-1q.88 0 1.358-.5q.476-.5 1.646-.5t1.64.5t1.352.5t1.358-.5t1.646-.5t1.646.5t1.358.5t1.333-.5t1.62-.5t1.678.5t1.365.5v1q-1.17 0-1.616-.5t-1.326-.5t-1.383.5t-1.671.5t-1.646-.5t-1.358-.5t-1.358.5M3 9.616V9q0-2.356 2.088-3.678T12 4t6.913 1.322T21 9v.616z");
}

</style>
