<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm-t66byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-alert-rounded" /></template>
<style>
.sm-t66byv {
  fill: currentColor;
  d: path("M8.696 21q-.352 0-.581-.232q-.23-.233-.23-.576V5.288q0-.343.232-.575t.575-.232h1.616v-.673q0-.344.232-.576T11.116 3h1.769q.343 0 .575.232t.232.576v.673h1.62q.344 0 .574.232t.23.575v14.904q0 .344-.233.576t-.575.232zm3.66-7.375q.144-.143.144-.356v-4q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356v4q0 .213.144.356t.357.144t.356-.144m-.358 3.067q.31 0 .521-.21q.21-.21.21-.52t-.21-.52q-.209-.211-.52-.211t-.52.21t-.21.52t.21.52q.209.211.52.211");
}

</style>
