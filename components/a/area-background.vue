<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="udkxzxsow"/><path class="q3tl-6b-e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:area-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q3tl-6b-e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4L8.21 9.895h1.895L12 6.72l1.895 3.175h1.895zm0 16l-3.79-5.895h1.895L12 17.28l1.895-3.175h1.895zm-4.421-8.842l-1.474 1.684h11.79l-1.474-1.684z");
}

.udkxzxsow {
  fill: var(--svg-color--b8a874, #b8a874);
  d: path("M24 0H0v24h24z");
}

</style>
