<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7pts169v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:docking-station" /></template>
<style>
.l7pts169v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.875 2.25h-7.75q-1.398 0-2.386.989q-.989.988-.989 2.386v3.75q0 1.067.576 1.895q-.132.032-.245.108t-.191.186l-2.5 3.5q-.087.121-.121.267q-.033.145-.009.292q.025.147.104.274t.2.213q.196.14.436.14h8.25v1.25H4.125q-2.375 0-2.375 2.375q0 .984.696 1.679q.695.696 1.679.696h15.75q.984 0 1.679-.696q.696-.695.696-1.679t-.696-1.679q-.695-.696-1.679-.696H12.75v-1.25H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.24-.14-.436l-2.5-3.5q-.079-.11-.191-.186q-.113-.076-.245-.108q.576-.828.576-1.895v-3.75q0-1.398-.989-2.386q-.988-.989-2.386-.989M12 14.75H4.457l1.653-2.314q.085-.119.12-.262q.828.576 1.895.576h7.75q1.067 0 1.895-.576q.035.143.12.262l1.653 2.314z");
}

</style>
