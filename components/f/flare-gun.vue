<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbz3-bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flare-gun" /></template>
<style>
.jmbz3-bgf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.386 12.911l8.228-4.75a1.75 1.75 0 0 1 2.39.64l.25.433a1.75 1.75 0 0 1-.64 2.391l-2.956 1.707a1.75 1.75 0 0 0-.818 1.961l.771 2.928a1.75 1.75 0 0 1-.818 1.96l-.574.332a1.596 1.596 0 0 1-2.323-.91L7.152 17.2a.898.898 0 0 0-1.307-.512a1.125 1.125 0 0 1-1.537-.412l-.562-.975a1.75 1.75 0 0 1 .64-2.39M15.5 4.5v-2M18 6l2-2m-1.25 4.5h2.75");
}

</style>
