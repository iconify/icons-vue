<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2pkxybvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:collar-tag" /></template>
<style>
.m2pkxybvq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6q0-1.76 1.245-3.005T12 1.75t3.005 1.245T16.25 6q0 .706-.2 1.329q.854.511 1.607 1.264Q20 10.936 20 14.25t-2.343 5.657T12 22.25t-5.657-2.343T4 14.25t2.343-5.657q.753-.753 1.607-1.264q-.2-.623-.2-1.329");
}

</style>
