<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkp8kpbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-canister" /></template>
<style>
.mkp8kpbid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25h11q2.75 0 2.75 2.75q0 2.031-1.5 2.562V19q0 2.75-2.75 2.75H8q-2.75 0-2.75-2.75V7.562Q3.75 7.031 3.75 5q0-2.75 2.75-2.75m.25 5.5V19q0 1.25 1.25 1.25h8q1.25 0 1.25-1.25V7.75zm3.75 2h3q2.5 0 2.5 2.5v3.5q0 2.5-2.5 2.5h-3q-2.5 0-2.5-2.5v-3.5q0-2.5 2.5-2.5");
}

</style>
