<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chl5rhp2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-sharp" /></template>
<style>
.chl5rhp2b {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zM6 7h8V5H6zm0 4h8V9H6zm0 8h12v-6h-2v1.825q.35.25.55.625t.2.8q0 .725-.513 1.238T15 18t-1.237-.513t-.513-1.237q0-.425.2-.8t.55-.625V13H6zM16 7h2V5h-2zm0 4h2V9h-2z");
}

</style>
