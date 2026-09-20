<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGLymAicej)" class="i2o7mbbxe"/><defs><linearGradient id="SVGLymAicej" x1="20.985" x2="3.002" y1="8.244" y2="8.244" gradientUnits="userSpaceOnUse"><stop class="r-xrmhbkv"/><stop offset="1" class="wn7x46btp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dck" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i2o7mbbxe {
  d: path("m17.714 8.176l-.018.005l-8.66 8.836a1.247 1.247 0 0 1-1.787.01L3.44 13.17c-.932-.935-.28-2.52 1.02-2.52h2.192c.382 0 .751.15 1.03.42l2.025 1.947l-1.035 1.125l-2.025-1.917H4.59l3.55 3.528l8.494-8.693a1.5 1.5 0 0 1 1.08-.459h1.647c1.462 0 2.191 1.818 1.147 2.875l-7.45 7.528a1.32 1.32 0 0 1-1.899-.018l-.509-.527l1.08-1.084l.387.405l7.334-7.38c.081-.08.023-.225-.09-.225H17.71z");
}

.r-xrmhbkv {
  stop-color: var(--svg-color--097cb8, #097cb8);
}

.wn7x46btp {
  stop-color: var(--svg-color--8adecf, #8adecf);
}

</style>
