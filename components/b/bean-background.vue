<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iq1dzuscl"/><path clip-rule="evenodd" class="ss69frr7r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bean-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iq1dzuscl {
  fill: var(--svg-color--b31f39, #b31f39);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ss69frr7r {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.689 4.337c-3.136-1.151-5.582.8-6.853 3.556c-1.576 3.397-1.8 8.654 1.776 10.945a8.08 8.08 0 0 0 7.133.6a4.7 4.7 0 0 0 1.83-1.18c1.201-1.301.58-2.867-.15-4.192l-.315-.54c-.485-.826-.985-1.666-.97-2.667c0-.355.095-.75.19-1.145c.065-.27.13-.55.165-.81c.3-2.257-.8-3.832-2.806-4.567m-3.642 5.187c.46 0 .836-.375.836-.84a.84.84 0 0 0-.836-.841a.837.837 0 0 0-.83.84c0 .466.375.84.83.84m3.352 1.23c.465 0 .835-.38.835-.84c0-.465-.37-.84-.83-.84a.841.841 0 0 0 0 1.68z");
}

</style>
