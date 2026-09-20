<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ullgkjxxs"/><path class="sorvgj00u"/><path class="kmdad35cp"/><path class="d6vxpybyf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitkub-chain-background" /></template>
<style>
.d6vxpybyf {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.207 11.257l-.011.01a1.03 1.03 0 0 0-.003 1.454l.01.011a1.03 1.03 0 0 0 1.455.003l.01-.01a1.03 1.03 0 0 0 .003-1.455l-.01-.01a1.03 1.03 0 0 0-1.454-.003");
}

.ft5dv1b6b {
  fill: none;
}

.kmdad35cp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.121 6.879L8.02 7.975l.007.007l-2.938 2.924v-.005L4 11.984l.004.004l-.004.005l1.077 1.08l4.009 4.049s.947-1.25.016-2.187l-2.935-2.948L9.104 9.06l1.482 1.492c1.264 1.27 2.165-.028 2.165-.028zm10.865 5.13l.014-.014l-5.069-5.09s-.93 1.217-.049 2.102l2.993 3.006l-2.93 2.918l-1.37-1.375c-.982-.987-2.283-.093-2.283-.093l3.611 3.625l5.09-5.07z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sorvgj00u {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.346 11.257l-.01.01a1.03 1.03 0 0 0-.004 1.454l.011.011c.4.403 1.052.404 1.454.003l.011-.01a1.03 1.03 0 0 0 .003-1.455l-.01-.01a1.03 1.03 0 0 0-1.455-.003");
}

.ullgkjxxs {
  fill: var(--svg-color--02d767, #02d767);
  d: path("M24 0H0v24h24z");
}

</style>
