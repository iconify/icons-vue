<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgmt6_nsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-cath" /></template>
<style>
.tgmt6_nsw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.361 17.391q-1.609-.977-2.867-1.975q-.192.265-.394.534l-.014.019q-2.854 3.566-7.2 6.174q-.128.077-.276.099q-.147.022-.292-.014q-.145-.037-.264-.125q-.12-.089-.197-.217q-.038-.063-.063-.133t-.036-.143t-.007-.146q.003-.074.021-.146t.05-.138t.075-.127q.044-.059.099-.108q.055-.05.118-.088q4.11-2.466 6.793-5.816q.229-.306.445-.605Q6 11.321 6 8q0-1.845 1.239-3.143Q8.534 3.5 10.5 3.5q1.954 0 3.25 1.475Q15.046 3.5 17 3.5q1.966 0 3.261 1.357Q21.5 6.155 21.5 8q0 4.922-7.361 9.391q-.088.054-.187.081t-.202.028t-.202-.028q-.099-.027-.187-.081M11.5 9q0 1.75 1.75 1.75T15 9t-1.75-1.75T11.5 9");
}

</style>
