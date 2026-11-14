<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9rsju6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beware-of-dog" /></template>
<style>
.rk9rsju6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.244 16.955L14.5 19H11l-1-4H5q-.074 0-.147-.007t-.146-.022q-.072-.014-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087t-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126t-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T3.5 13.5V11q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T5 9.5h4L11.5 7l2-4.5L16 7c1.64 1.093 2.218 2.984 1.635 4.703M12.5 10h.01M18 14.5V18m0 3h.01");
}

</style>
