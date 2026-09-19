<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pyk2-o_db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:loterija-slovenije" /></template>
<style>
.pyk2-o_db {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 5.5c3.324 0 6 2.676 6 6V22H11.5c-3.324 0-6-2.676-6-6c0-5.799 4.701-10.5 10.5-10.5m16 0c-3.324 0-6 2.676-6 6V22h10.5c3.324 0 6-2.676 6-6c0-5.799-4.701-10.5-10.5-10.5m-16 37c3.324 0 6-2.676 6-6V26H11.5c-3.324 0-6 2.676-6 6c0 5.799 4.701 10.5 10.5 10.5m16 0c-3.324 0-6-2.676-6-6V26h10.5c3.324 0 6 2.676 6 6c0 5.799-4.701 10.5-10.5 10.5");
}

</style>
