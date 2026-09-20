<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d6ralzhdc"/><path clip-rule="evenodd" class="jkiy6wd8j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:infra-background" /></template>
<style>
.d6ralzhdc {
  fill: var(--svg-color--fdb913, #fdb913);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jkiy6wd8j {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 4l6.588 5.647v4.706L12 20l-6.588-5.402V9.647zm-6.118 6.25v3.736l2.278-1.868zm2.654 2.174l-2.517 2.06l5.746 4.707v-4.118zm3.7 2.649v4.108l5.74-4.922l-2.428-1.901zm3.689-3.026l2.192 1.718v-3.516zm2.06-2.296l-2.446 2l-3.304-2.589V4.824zm-6.22-4.927v4.343l-3.229 2.65l-2.522-2.071l5.75-4.918zM12 9.58l-3.092 2.541L12 14.65l3.167-2.597l-3.162-2.476z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
