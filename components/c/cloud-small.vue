<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxthb7bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-small" /></template>
<style>
.rxthb7bvm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 1.75H6.875q-2.123 0-3.624 1.501T1.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T17.125 1.75M9.25 16.25q-1.346 0-2.298-.952T6 13q0-2.998 2.765-3.23q.971-1.827 3.143-2.016q2.215-.192 3.494 1.508q3.098.195 3.098 3.488q0 1.45-1.025 2.475T15 16.25z");
}

</style>
