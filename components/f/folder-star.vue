<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c41w3ybdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-star" /></template>
<style>
.c41w3ybdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm8.16 6.309l.118.277q.176.412.623.452l.301.027q.83.075 1.087.867q.256.792-.371 1.339l-.227.198q-.338.295-.238.733l.067.294q.186.811-.487 1.301t-1.388.063l-.26-.155q-.385-.231-.77 0l-.259.155q-.716.427-1.389-.063t-.487-1.302l.067-.292q.1-.439-.238-.734l-.227-.198q-.627-.547-.371-1.339q.257-.792 1.087-.867l.3-.027q.448-.04.624-.453l.118-.276q.327-.766 1.16-.766t1.16.766");
}

</style>
