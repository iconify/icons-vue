<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="v7e7h4odi"/><path clip-rule="evenodd" class="etxhpchat"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apollo-background" /></template>
<style>
.etxhpchat {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.468 14.875A8 8 0 0 1 11.88 20l2.53-5.794a8.56 8.56 0 0 0 5.058.67m.056-.15q.07-.194.13-.395c-.534.11-1.084.17-1.654.17a8 8 0 0 1-3.39-.75l3.175-7.275l-.26-.26l-7 3.14a8 8 0 0 1-.18-5.183a8 8 0 0 1 9.18 10.554M9.784 4.311a8 8 0 0 0-5.779 7.964l6.06-2.715a8.48 8.48 0 0 1-.28-5.25m-5.745 8.5a7.98 7.98 0 0 0 2.35 4.893a8 8 0 0 1-.22-.228l5.41-5.405a8.5 8.5 0 0 1-1.32-2.05zm2.486 5.024a7.97 7.97 0 0 0 4.824 2.14l2.61-5.994a8.5 8.5 0 0 1-2.045-1.545zM16.74 7.61l-2.575 5.91a8 8 0 0 1-1.895-1.435zm-.375-.325l-4.435 4.43a8 8 0 0 1-1.215-1.9z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v7e7h4odi {
  fill: var(--svg-color--00dc55, #00dc55);
  d: path("M24 0H0v24h24z");
}

</style>
