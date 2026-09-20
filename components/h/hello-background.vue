<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="kz0l_5b8f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hello-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kz0l_5b8f {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.766 5.216a7.993 7.993 0 0 0 0 13.568zm2.823 14.659a8 8 0 0 0 2.822 0v-5.927l-2.822.362zm5.645-1.091a7.993 7.993 0 0 0 0-13.568zm-2.823-14.66v7.006l-2.822.4V4.125a8 8 0 0 1 2.822 0");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
