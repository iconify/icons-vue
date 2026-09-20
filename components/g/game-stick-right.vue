<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egoqm49px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-right" /></template>
<style>
.egoqm49px {
  fill: currentColor;
  d: path("M16.27 14.658v2.727q0 .67-.473 1.143q-.472.472-1.143.472H9.327q-.671 0-1.143-.472t-.472-1.144v-2.726q-2.121-.666-3.417-1.851T3 10.133q0-2.14 2.624-3.646T12 4.98t6.376 1.506T21 10.133q0 1.488-1.295 2.674t-3.436 1.85m-5.902-1.891h.77v-2.012h.911l1.242 2.012h.893l-1.43-2.22q.5-.194.763-.528t.263-.845q0-.73-.469-1.127q-.468-.396-1.377-.396h-1.566zm.77-2.685V8.37h.717q.573 0 .852.213t.278.626q0 .438-.269.655q-.269.216-.848.216z");
}

</style>
