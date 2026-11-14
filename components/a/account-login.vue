<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo1warhdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-login" /></template>
<style>
.yo1warhdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.195 0 2.312.178 3.299.506M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 11h3.75m-2-2l2 2l-2 2m3.25-5.5h2v7h-2");
}

</style>
