<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oi-vu8a6f"/><path class="sqv7qnfow"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fra-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oi-vu8a6f {
  fill: var(--svg-color--73f, #73f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sqv7qnfow {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.647 6.972a.16.16 0 0 0 .213.112l7.821-2.016c.187-.042.165-.303-.032-.32l-8.583-.746c-.123-.005-.214.096-.182.203l.763 2.772zm.784 4.926l-1.141-4.1l-.15-.533l-.613-2.18c-.042-.16-.277-.16-.325 0l-2.196 7.858c-.032.123.08.234.213.202l4.089-1.05c.085-.016.139-.106.117-.197zm8.87-6.675a.58.58 0 0 1 .635.25l2.042 3.413c.054.085.005.208-.106.24L9.198 11.86a.16.16 0 0 1-.213-.112L7.892 7.814c-.032-.09.021-.181.117-.203zm-8.636 7.523a.16.16 0 0 0-.213-.107l-4.09 1.05c-.122.027-.17.187-.08.267l6.015 5.827c.127.117.33.005.293-.16l-1.92-6.872zm.672-.347L19.52 9.776c.165-.037.282.139.181.267l-8.157 9.895c-.085.106-.256.064-.299-.064L9.22 12.602c-.032-.086.026-.176.117-.203");
}

</style>
