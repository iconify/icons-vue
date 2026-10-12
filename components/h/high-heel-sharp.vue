<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oitue3cpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:high-heel-sharp" /></template>
<style>
.oitue3cpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.25v-2.5h2C8 15.75 10.5 14 12.5 11l2.25-3.5l1.542-2.472L17.75 7.55l3.5 5.7v2.25c-4.25 0-7.75 1.5-9.75 3.75H2.75zm17.25-2v5");
}

</style>
