<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvlbtgfwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:atom-nucleus" /></template>
<style>
.nvlbtgfwg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 8.25q0-2.175 1.538-3.712Q9.825 3 12 3t3.712 1.538Q17.25 6.075 17.25 8.25q0 1.377-.617 2.499q2.09.046 3.58 1.537Q21.751 13.825 21.75 16q.001 2.175-1.537 3.714q-1.538 1.538-3.713 1.538t-3.713-1.538q-.464-.464-.788-.986q-.323.521-.787.984Q9.675 21.25 7.5 21.25t-3.712-1.538Q2.25 18.175 2.25 16t1.538-3.712q1.491-1.491 3.58-1.537Q6.75 9.629 6.75 8.25");
}

</style>
