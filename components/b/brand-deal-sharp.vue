<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iqy4aclou"/><path class="gchdwyzem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brand-deal-sharp" /></template>
<style>
.gchdwyzem {
  d: path("m12.14 11.07l.69 1.53l.14.32l.35.03l1.66.18l.35.04l-.26.23l-1.24 1.13l-.26.23l.07.34l.35 1.64l.07.34l-.31-.17l-1.45-.84l-.3-.17l-.3.17l-1.45.84l-.31.17l.07-.34l.35-1.64l.07-.34l-.26-.23l-1.24-1.13l-.26-.23l.35-.04l1.66-.18l.35-.03l.14-.32l.69-1.53l.14-.32z");
}

.iqy4aclou {
  d: path("M8.75 7.25v-3.5h6.5v3.5m-12.5 0h18.5v13.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
