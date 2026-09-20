<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3lbchwgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-2-outline-sharp" /></template>
<style>
.z3lbchwgl {
  fill: currentColor;
  d: path("M4 22V8H2V5q0-1.25.875-2.125T5 2h14q1.25 0 2.125.875T22 5v3h-2v14zm2-2h12v-3H6zm0-5h12v-3h-2v1q0 .425-.288.713T15 14t-.712-.288T14 13v-1H6zm0-5h8V8H6zm10 0h2V8h-2zM4 6h16V5q0-.425-.288-.712T19 4H5q-.425 0-.712.288T4 5zm16 0H4z");
}

</style>
