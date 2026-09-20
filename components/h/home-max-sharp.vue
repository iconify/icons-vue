<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a28e22wqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-max-sharp" /></template>
<style>
.a28e22wqn {
  fill: currentColor;
  d: path("M7 20v-1H5q-1.65 0-2.825-1.175T1 15V9q0-1.65 1.175-2.825T5 5h14q1.65 0 2.825 1.175T23 9v6q0 1.65-1.175 2.825T19 19h-2v1z");
}

</style>
