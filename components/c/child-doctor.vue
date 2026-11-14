<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a_f-o7t6h"/><path class="xc18ddbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-doctor" /></template>
<style>
.a_f-o7t6h {
  d: path("M12.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.544 0 1.065.048M6.573 7.761q.033.17.08.336q.048.166.109.327t.136.316t.164.304t.188.288q.101.141.213.272q.113.131.236.251q.123.121.256.231t.275.208q.142.097.292.183t.307.157t.319.131q.162.058.329.102t.337.074t.342.044q.171.015.344.015q.174 0 .348-.015q.173-.015.345-.045q.171-.031.34-.076q.168-.045.332-.104q.163-.059.321-.133q.158-.073.309-.16t.294-.187t.277-.211t.257-.235t.235-.256q.113-.133.213-.275t.188-.294q.087-.15.161-.308q.074-.157.134-.321q.06-.163.106-.332q.046-.168.077-.339M8.75 5.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm1.75 0h.01M15 18.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xc18ddbrq {
  fill: currentColor;
  d: path("M14.25 15.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
