<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjmz8i2uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:girl-sharp" /></template>
<style>
.vjmz8i2uk {
  fill: currentColor;
  d: path("M10.763 6.988q-.513-.513-.513-1.238t.513-1.237T12 4t1.238.513t.512 1.237t-.513 1.238T12 7.5t-1.237-.513M10 20v-4H8l2.375-6.375q.2-.5.638-.812T12 8.5t.988.313t.637.812L16 16h-2v4z");
}

</style>
