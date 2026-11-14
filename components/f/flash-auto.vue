<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnb5d7-aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flash-auto" /></template>
<style>
.vnb5d7-aa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.126 6.061l-3.101 4.651A1.472 1.472 0 0 0 6.25 13h.782a1.75 1.75 0 0 1 1.738 1.954L8.5 17.25a1.027 1.027 0 0 0 1.874.689l3.101-4.651A1.472 1.472 0 0 0 12.25 11h-.782A1.75 1.75 0 0 1 9.73 9.046L10 6.75a1.027 1.027 0 0 0-1.874-.689M15.5 21l2.75-7L21 21m-4.5-2.25H20");
}

</style>
