<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkln_dbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:attacktheblock" /></template>
<style>
.pkln_dbas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.38 5.5H24v24.13H5.98zM5.98 29.63V42.5L17.5 29.63m8.88 0l3.84 4.3H17.78l3.85-4.3M25.62 5.5H24v24.13h18.02zm16.4 24.13V42.5L30.5 29.63");
}

</style>
