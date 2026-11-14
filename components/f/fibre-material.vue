<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4crttbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fibre-material" /></template>
<style>
.w4crttbaj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 1.75H6.25q-2.5 0-2.5 2.5t2.5 2.5h.5v10.5h-.5q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h11.5q1.036 0 1.768-.732t.732-1.768q0-2.5-2.5-2.5h-.5V6.75h.5q1.036 0 1.768-.732t.732-1.768q0-2.5-2.5-2.5m-9.5 10.791l7.5-2.5v7.209h-7.5zm7.5-4.082l-7.5 2.5V6.75h7.5z");
}

</style>
