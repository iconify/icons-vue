<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dzhsxqbte"/><path class="bcd684bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-switcher" /></template>
<style>
.bcd684bmq {
  d: path("M15.5 16.5L18 14l2.5 2.5m-5 3L18 22l2.5-2.5");
}

.dzhsxqbte {
  d: path("M13.6 21.5H4.5v-19h15v9.1m-11-9.1v19m3-14.5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
