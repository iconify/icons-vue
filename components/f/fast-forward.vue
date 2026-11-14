<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj_hbkawn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fast-forward" /></template>
<style>
.cj_hbkawn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.691 7.335l3.716 2.622q1.059.747 1.059 2.043t-1.059 2.043l-3.716 2.622q-1.241.876-2.591.177q-1.349-.699-1.35-2.219V9.377q.001-1.52 1.35-2.219t2.591.177m-9.5 0Q4.95 6.459 3.6 7.158q-1.349.699-1.35 2.219v5.246q.001 1.52 1.35 2.219t2.591-.177l3.716-2.622q1.059-.747 1.059-2.043T9.907 9.957z");
}

</style>
