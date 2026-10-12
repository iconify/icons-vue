<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7h03bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cannula-sharp" /></template>
<style>
.mh7h03bqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12h5m1-2h1l.15-.99l.45-3.02l.15-.99h2.25l.15.99l.45 3.02l.15.99h2v4h-2l-.15.99l-.45 3.02l-.15.99H10.5l-.15-.99l-.45-3.02l-.15-.99h-2v-4zm9.25.5h3.25v3H18z");
}

</style>
