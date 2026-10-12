<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejhlx8b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:firewall-sharp" /></template>
<style>
.ejhlx8b6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15h18.5v6.25H2.75zm0 3.25h18.5M8.5 15v3.25m7-3.25v3.25m-3.5 0v3m0-18.5c.45 1.75 1.8 2.75 2.6 3.9l.65 1.011V8.75a3.25 3.25 0 0 1-6.5 0V7.329l1.1-1.179l.394 1.341l.956.159l-.079-2.67z");
}

</style>
