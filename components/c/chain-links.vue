<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i32czfbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chain-links" /></template>
<style>
.i32czfbyy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.248 4.752Q20.64 6.143 20.64 8.11t-1.392 3.359l-.354.354q-1.391 1.392-3.358 1.392q-.729 0-1.378-.191l1.2-1.201q1.591-1.59 0-3.181t-3.181 0l-1.201 1.2q-.191-.649-.191-1.377q0-1.968 1.392-3.359l.354-.354Q13.922 3.36 15.89 3.36t3.358 1.392m-9.406 6.224q-.649-.191-1.377-.191q-1.968 0-3.359 1.392l-.354.354Q3.36 13.922 3.36 15.89t1.392 3.358q1.391 1.392 3.359 1.392t3.358-1.392l.354-.354q1.392-1.391 1.392-3.358q0-.729-.191-1.378l-1.201 1.2q-1.59 1.591-3.181 0t0-3.181z");
}

</style>
