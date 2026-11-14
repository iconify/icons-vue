<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flpf_jbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-watch" /></template>
<style>
.flpf_jbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V20M6 9.5h7M3.5 13c0 4 2.75 7 6 7c1.767 0 3.386-.887 4.495-2.338m1.422-3.477Q15.5 13.61 15.5 13m.25 7.25h5.5m-4.5 0V17.5a1.75 1.75 0 0 1 3.5 0v2.75");
}

</style>
