<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyow673uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:c-table" /></template>
<style>
.lyow673uq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q2.25 0 2.25 2.25T18 7.25H7.75v9.5H18q2.25 0 2.25 2.25T18 21.25H6q-2.25 0-2.25-2.25T6 16.75h.25v-9.5H6Q3.75 7.25 3.75 5T6 2.75");
}

</style>
