<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvppozbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:double-switch" /></template>
<style>
.kvppozbxd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25m3.875 7q0-2.5-2.5-2.5t-2.5 2.5v5.5q0 2.5 2.5 2.5t2.5-2.5zm4-2.5q-2.5 0-2.5 2.5v5.5q0 2.5 2.5 2.5t2.5-2.5v-5.5q0-2.5-2.5-2.5");
}

</style>
