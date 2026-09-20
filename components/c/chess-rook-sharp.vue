<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xorbsebsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-rook-sharp" /></template>
<style>
.xorbsebsm {
  fill: currentColor;
  d: path("M4 22v-5q2.025-1.625 3.05-3.525T8.5 10H6V2h5v3h2V2h5v8h-2.525q.425 1.575 1.45 3.475T20 17v5z");
}

</style>
