<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="visbnuboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:girl-outline-rounded" /></template>
<style>
.visbnuboj {
  fill: currentColor;
  d: path("M10.763 6.988q-.513-.513-.513-1.238t.513-1.237T12 4t1.238.513t.512 1.237t-.513 1.238T12 7.5t-1.237-.513M10 19v-3h-.55q-.525 0-.837-.425T8.5 14.65l1.875-5.025q.2-.5.637-.813T12 8.5t.988.313t.637.812L15.5 14.65q.2.5-.112.925T14.55 16H14v3q0 .425-.288.713T13 20h-2q-.425 0-.712-.288T10 19");
}

</style>
