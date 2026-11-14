<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5z6p6b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:block-confirmed" /></template>
<style>
.l5z6p6b1z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 2.25h-7.5q-2.485 0-4.243 1.757Q2.25 5.765 2.25 8.25v7.5q0 2.485 1.757 4.243Q5.765 21.75 8.25 21.75h7.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-7.5q0-2.485-1.757-4.243Q18.235 2.25 15.75 2.25m-5.272 12.168l5.471-5.927q.05-.054.11-.097q.059-.044.127-.075q.067-.031.138-.048t.146-.02t.147.008t.142.037t.132.064t.118.089q.109.101.172.237t.068.284t-.045.289q-.052.14-.153.25l-6 6.5l-.021.021q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3-3q-.106-.105-.163-.243T6.75 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094z");
}

</style>
