<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_1hsr7ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:correction-notice" /></template>
<style>
.a_1hsr7ao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.9V19q0 .074-.007.147t-.022.146q-.014.072-.036.142q-.021.071-.049.139t-.063.133t-.076.126q-.041.062-.087.119q-.047.057-.099.109t-.109.099t-.119.087t-.126.076t-.133.063t-.139.049t-.142.036q-.073.015-.146.022T4.5 20.5t-.147-.007t-.146-.022q-.072-.014-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T3 19V9h2.057m2.4-5.5H20.5v13.057M16.569 20.5H4.5m7.5-13h5.5m-8.5 9h3.5m-9-13l17 17");
}

</style>
