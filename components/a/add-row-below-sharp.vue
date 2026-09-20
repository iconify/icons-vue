<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhv_y5bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-row-below-sharp" /></template>
<style>
.uhv_y5bbi {
  fill: currentColor;
  d: path("M4 10.558V3h16v7.558zM4 19v-7.442h16V19h-3.138q.011-.125.017-.244t.006-.256q0-2.027-1.421-3.456T12 13.615t-3.463 1.43T7.116 18.5q0 .134.015.25t.027.25zm7.5 2v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
