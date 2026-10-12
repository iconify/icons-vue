<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dih3mbc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crayons" /></template>
<style>
.dih3mbc5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.31 7.81l-2.12-2.12q-.71-.71-1.42 0L7.7 12.76q-.71.71 0 1.42l2.12 2.12q.71.71 1.42 0l7.07-7.07q.71-.71 0-1.42M10 16.48L7.52 14q-.53-.53-.85.15L5.26 17.1q-.32.68.21 1.21l.22.22q.53.53 1.21.21l2.95-1.41q.68-.32.15-.85m6.9-5.84L13.36 7.1m-.7 7.78l-3.54-3.54");
}

</style>
