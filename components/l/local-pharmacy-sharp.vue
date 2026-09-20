<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7r22ol5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-pharmacy-sharp" /></template>
<style>
.m7r22ol5t {
  fill: currentColor;
  d: path("M4 20v-.846L6.039 13L4 6.846V6h12.085l1.334-3.692l1.042.388L17.274 6H20v.846L17.962 13L20 19.154V20zm7.5-3.692h1V13.5h2.808v-1H12.5V9.692h-1V12.5H8.692v1H11.5z");
}

</style>
