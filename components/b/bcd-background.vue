<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n5ip8irhc"/><path class="fvz0m2b2u"/><path class="l0vq6gtiw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fvz0m2b2u {
  fill: var(--svg-color--000, #000);
  d: path("M9.085 5.28h5.713l2.646 1.202L20 9.834l-8.06 8.886L4 9.834l2.507-3.35zm.09.403l-2.076.969l2.08 1.046h5.529l2.135-1.046l-2.132-.97zm8.08 1.216l-2.261 1.108l.942 3.34l3.49-1.602zm1.672 3.518l-2.978 1.368l-2.926 5.143zm-6.986 7.597l3.648-6.411l-.987-3.502H9.28l-1.03 3.502zm-4.035-6.669l.983-3.34L6.698 6.9l-2.13 2.846zM5.08 10.44l5.718 6.398l-2.91-5.054z");
}

.l0vq6gtiw {
  fill: var(--svg-color--000, #000);
  d: path("M13.76 10.194c-.06-.627-.72-.833-1.403-.889v-.8h-.403v.806h-.403v-.806h-.403v.8l-1.21.011v.801s.505-.011.494 0c.217 0 .29.117.313.228v2.028c-.003.109-.087.162-.191.162h-.615l-.002.806h1.211v.806h.403v-.806h.403v.806h.403v-.806c.89-.056 1.654-.323 1.726-1.162c.056-.673-.261-.973-.767-1.095c.306-.161.5-.434.445-.895zm-.728 1.824c.006.61-1.12.517-1.481.517v-1.023c.361 0 1.476-.178 1.481.506m-.345-1.561c0 .665-1.136.466-1.136.466v-.806c.295 0 1.136-.072 1.136.34");
}

.n5ip8irhc {
  fill: var(--svg-color--fdc337, #fdc337);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
