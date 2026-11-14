<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3qum8pgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cell-tower-lattice" /></template>
<style>
.y3qum8pgi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 4.25q0-2-2-2t-2 2v2q0 .268.036.5H9.5q-.064 0-.126.011q-.063.01-.123.031q-.06.022-.115.052q-.056.031-.105.071q-.05.04-.092.087q-.042.048-.076.102t-.057.112q-.024.059-.038.121l-1.5 6.75l-1.5 6.75q-.035.156-.003.312q.031.156.124.285l.023.032q.08.101.19.17q.109.068.235.096l.038.007l.034.005q.129.016.256-.012q.128-.029.238-.099l.031-.022L12 18.012l5.066 3.599l.031.022q.126.08.273.106t.293-.007q.136-.03.252-.107t.196-.191l.022-.031q.08-.126.106-.273t-.007-.293v-.001l-1.5-6.748v-.001l-1.5-6.75q-.014-.062-.038-.121t-.057-.112t-.076-.102q-.042-.047-.092-.087t-.105-.071t-.115-.052t-.123-.031q-.062-.011-.126-.011h-.536q.036-.232.036-.5zM13.65 15L12 16.172L10.35 15zm-.355 2.092l2.218-1.576l.832 3.743zm-2.59 0l-3.05 2.167l.832-3.743zm4.36-3.592h-6.13l1.167-5.25h3.796z");
}

</style>
