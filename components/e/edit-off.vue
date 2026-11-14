<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0fz2-blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:edit-off" /></template>
<style>
.m0fz2-blj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.233 8.231l3.479-3.479q.052-.052.109-.099t.118-.088q.062-.041.127-.075q.065-.035.133-.063q.068-.029.138-.05t.143-.036t.146-.021q.073-.008.147-.008t.147.008q.073.007.146.021q.072.015.143.036t.138.05q.068.028.133.063q.065.034.127.075q.061.041.118.088t.109.099l1.414 1.414q.052.052.099.109t.088.118q.041.062.075.127q.035.065.063.133q.029.068.05.138t.036.143t.021.146q.008.073.008.147t-.008.147t-.021.146q-.015.072-.036.143t-.05.138q-.028.068-.063.133q-.034.065-.075.127q-.041.061-.088.118t-.099.109l-3.52 3.52m-3.96 3.96l-1.614 1.614q-.275.275-.649.382l-2.101.6q-.092.026-.186.04t-.189.015t-.19-.01t-.187-.036q-.092-.023-.18-.059t-.171-.084t-.158-.105T6 18t-.125-.143t-.105-.158t-.084-.171t-.059-.18q-.024-.093-.036-.187q-.011-.095-.01-.19t.015-.189t.04-.186l.6-2.101q.107-.374.382-.649l1.655-1.655M3.5 3.5l17 17");
}

</style>
