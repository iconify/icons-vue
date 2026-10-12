<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6cxgkght"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circular-saw-site-sharp" /></template>
<style>
.b6cxgkght {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.54 12.78l-.75-.79l-.2-.22l.07-.29l.25-1.06l.07-.29l-.29-.09l-1.04-.31l-.29-.09l-.09-.29l-.31-1.04l-.08-.29l-.3.07l-1.06.25l-.29.07l-.22-.2l-.79-.75l-.22-.21l-.22.21l-.79.75l-.22.2l-.29-.07l-1.06-.25l-.29-.07l-.09.29l-.31 1.04l-.09.29l-.29.09l-1.04.31l-.29.09l.07.29l.25 1.06l.07.29l-.2.22l-.75.79l-.21.22h11.5zM2.75 13h18.5v2.5H2.75zM5 15.5l-1.25 5.75M19 15.5l1.25 5.75M4.4 18.5h15.2");
}

</style>
