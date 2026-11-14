<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esq479b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flare-gun" /></template>
<style>
.esq479b1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.871 13.786l11.258-6.5l2 3.464L10.5 14l1.451 5.513l-3.464 2l-1.668-5.388l-1.948 1.125ZM15.5 4.5v-2M18 6l2-2m-1.25 4.5h2.75");
}

</style>
