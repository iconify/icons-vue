<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf3sltbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:displaced-threshold" /></template>
<style>
.jf3sltbix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v19m12-19v19M9 2.75v5m3-5v5m3-5v5M6 10.5h12M12 21v-7.75m-2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>
