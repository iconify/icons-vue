<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6cih_wnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loyalty-tier-ladder" /></template>
<style>
.v6cih_wnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5v-3h6V15h6v-3.25h7v9.75ZM18 3.5l1.029 1.834l2.062.412l-1.427 1.545l.246 2.088L18 8.5l-1.91.879l.246-2.088l-1.427-1.545l2.062-.412Z");
}

</style>
