<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="zvvz40uai"/><path class="l0_r6sg3m"/><path class="uq88ifw0x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eco-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l0_r6sg3m {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.225 7A6.83 6.83 0 0 1 12 11.009A6.83 6.83 0 0 1 5.775 7a7.6 7.6 0 0 0-.7 1.023A7.99 7.99 0 0 0 12 12.007a7.99 7.99 0 0 0 6.924-3.984A8 8 0 0 0 18.225 7m-7.723 12.83c.1-4.338 3.595-7.823 7.888-7.823c.55 0 1.078.055 1.598.165q-.014.526-.095 1.043a6.7 6.7 0 0 0-1.653-.21a6.79 6.79 0 0 0-6.278 4.325a6.8 6.8 0 0 0-.461 2.64a7 7 0 0 1-.999-.14");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uq88ifw0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.974 12.447c-.234 3.575-3.355 6.55-6.974 6.55q-.407.001-.804-.05l-.125.999a7.987 7.987 0 0 0 8.877-7.115l-.959-.329l-.015-.06zm-.215-4.703a7.983 7.983 0 0 0-14.747 4.264a7.98 7.98 0 0 0 2.896 6.155l.819-.684a7.04 7.04 0 0 1-2.716-5.471c0-3.764 3.225-6.99 6.989-6.99a7.09 7.09 0 0 1 6 3.485z");
}

.zvvz40uai {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.379 17.68q.398.383.848.714a7.9 7.9 0 0 0 3.275-6.385c0-2.611-1.288-4.928-3.28-6.385q-.448.331-.843.713a6.76 6.76 0 0 1 3.125 5.672c0 2.366-1.238 4.448-3.125 5.671");
}

</style>
