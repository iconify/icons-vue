<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct4emnf-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:descaler" /></template>
<style>
.ct4emnf-o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75h2q2.25 0 2.25 2.25q0 1.061-.5 1.621v1.504l3.7 2.775q.07.052.126.119t.095.146t.059.163t.02.172V20q0 2.25-2.25 2.25h-9q-2.25 0-2.25-2.25v-9.5q0-.087.02-.172t.059-.163q.039-.079.095-.146T5.55 9.9l3.7-2.775V5.621q-.5-.56-.5-1.621q0-2.25 2.25-2.25m-.25 4.493V7.5q0 .087-.02.172t-.059.163t-.095.146t-.126.119l-3.7 2.775V20q0 .75.75.75h9q.75 0 .75-.75v-9.125L13.55 8.1q-.07-.052-.126-.119t-.095-.146t-.059-.163t-.02-.172V6.243q-.121.007-.25.007h-2q-.129 0-.25-.007m3.245 7.959l.525 1.007q.586 1.123-.07 2.207q-.657 1.083-1.924 1.084h-1.052q-1.267-.001-1.924-1.084q-.656-1.084-.07-2.207l.525-1.007q.631-1.209 1.995-1.209t1.995 1.209");
}

</style>
