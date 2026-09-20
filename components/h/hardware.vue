<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt4w8ubvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hardware" /></template>
<style>
.dt4w8ubvw {
  fill: currentColor;
  d: path("M10.27 11.5V7H5.845q.289-1.325 1.357-2.162Q8.27 4 9.653 4h4.616v2.885L17.154 4h1v6.77h-1l-2.885-2.885V11.5zm.769 8.5q-.31 0-.54-.23t-.23-.54v-6.71h4v6.71q0 .31-.23.54T13.5 20z");
}

</style>
