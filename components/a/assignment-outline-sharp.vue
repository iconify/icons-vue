<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg6rk_wgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assignment-outline-sharp" /></template>
<style>
.bg6rk_wgb {
  fill: currentColor;
  d: path("M3 21V3h6.2q.325-.9 1.088-1.45T12 1t1.713.55T14.8 3H21v18zm2-2h14V5H5zm2-2h7v-2H7zm0-4h10v-2H7zm0-4h10V7H7zm5.538-4.962q.212-.213.212-.538t-.213-.537T12 2.75t-.537.213t-.213.537t.213.538t.537.212t.538-.213M5 19V5z");
}

</style>
