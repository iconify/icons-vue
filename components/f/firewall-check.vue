<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f6n9ntb9f"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firewall-check" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.f6n9ntb9f {
  d: path("M13.343 20.5H4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T2.5 19v-7q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 10.5h16q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T21.5 12v.279m-.011 6.904q-.015.119-.048.235q-.034.115-.085.224t-.12.208t-.152.187t-.179.159q-.096.073-.202.129t-.221.095t-.233.059M12 2.5s-3 2.25-3 4a3 3 0 0 0 6 0c0-1.75-3-4-3-4Zm-9.5 13h9.75m-4.75-5v5m0 0v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
