<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4__02y5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:javelin" /></template>
<style>
.y4__02y5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.25 20.75l6.19-6.19m2.12-2.12l6.19-6.19m2.75-2.57L18.78 6.6q-.25.43-.6.08l-.86-.86q-.35-.35.08-.6l2.92-1.72q.43-.25.18.18m-8.65 9.05l-.58-.58q-.35-.35-.7 0l-1.42 1.42q-.35.35 0 .7l.58.58q.35.35.7 0l1.42-1.42q.35-.35 0-.7m-8.6 2.02l3.5-3.5m2.5 9.5l3.5-3.5");
}

</style>
