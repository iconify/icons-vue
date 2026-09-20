<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t4qgnlb1t"/><path clip-rule="evenodd" class="o2km7sblu"/><path clip-rule="evenodd" class="tfc5z-uqa"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:chrp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o2km7sblu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.5 10.24a1.25 1.25 0 0 1-.77 1.165A1.25 1.25 0 0 1 13 10.24a1.247 1.247 0 0 1 1.25-1.255a1.25 1.25 0 0 1 1.25 1.255m-1-.24a.5.5 0 1 1-1.001 0a.5.5 0 0 1 1 0m.25.5a.25.25 0 1 0 0-.5a.25.25 0 0 0 0 .5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t4qgnlb1t {
  fill: var(--svg-color--f24139, #f24139);
  d: path("M24 0H0v24h24z");
}

.tfc5z-uqa {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12.375c0 3.395-1.92 6.31-4.695 7.625c2.24-2.385 2.2-5.32 2.195-5.91v-.065a1.3 1.3 0 0 1-.915.475c-1.565 0-3.085-1.27-4.7-2.99C10.275 9.8 9.5 7.925 9.5 7.295c0-.325.18-.54.3-.69l.075-.09c.07-.095.125-.17.125-.265c0-.245-.28-.245-.585-.245c-1.105 0-2.5.545-3.635 1.11A7.86 7.86 0 0 1 12 4c4.42 0 8 3.75 8 8.375M5.12 16.65c.51.9 1.183 1.697 1.985 2.35h1.86C11.04 19 13 17.635 13 15.45c0-2.18-1.96-3.94-4.035-3.94H4.04A8.87 8.87 0 0 0 4.79 16h7.71c-.685.335-2.45 1-4.035 1c-1.075 0-2.365-.175-3.345-.35M12 8.04C12 7.21 13.005 7 13.51 7C16.9 7 17 10.375 17 10.88c0 .075-.005.15-.02.245l1.635.415c.43.11.525.61.16.835L16.96 13.5l-.275-1.49c-.165.28-.4.49-.705.49c-.7 0-1.875-.88-2.47-1.41S12 9.08 12 8.04");
}

</style>
