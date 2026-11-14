<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trsd7bbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:billiard-ball" /></template>
<style>
.trsd7bbgq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m5.391-4.859Q5.75 8.532 5.75 10.5t1.391 3.359T10.5 15.25t3.359-1.391T15.25 10.5t-1.391-3.359T10.5 5.75T7.141 7.141");
}

</style>
