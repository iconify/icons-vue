<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojvh2abaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:announcement-off" /></template>
<style>
.ojvh2abaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m14.22 1.695v10.757l1.5 1.5V3.5q0-.162-.067-.31q-.031-.068-.074-.128t-.097-.11t-.117-.089t-.132-.065t-.142-.038t-.146-.01q-.074.003-.146.02t-.139.047L9.722 6.893l1.133 1.133zM7.838 16.25l10.237 4.653l-3.021-3.02l-6.304-2.866v-3.439l-1.5-1.5v4.672H4.5q-.75 0-.75-.75v-4q0-.75.75-.75h1.922l-1.5-1.5H4.5q-.932 0-1.591.659T2.25 10v4q0 .932.659 1.591t1.591.659z");
}

</style>
