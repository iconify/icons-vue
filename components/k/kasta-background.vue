<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m8tlzjbbf"/><path class="xa5zk1b8w"/><path clip-rule="evenodd" class="oppn_cbfa"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kasta-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m8tlzjbbf {
  fill: var(--svg-color--621efd, #621efd);
  d: path("M24 0H0v24h24z");
}

.oppn_cbfa {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.631 16.42v-3.158c0-1.052-.606-3.158-3.031-3.158c-2.708 0-3.285 2.396-3.285 3.158c0 .91.506 3.158 2.85 3.158c1.374 0 1.744-1.015 1.782-1.162v1.162zm-3.158-1.684a1.474 1.474 0 1 0 0-2.948a1.474 1.474 0 0 0 0 2.948");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xa5zk1b8w {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 7.58h1.684v5.01l2.282-2.484h1.929l-2.703 2.947L9.895 16H7.966l-2.282-2.488V16H4zm14.737 8.84a1.263 1.263 0 1 0 0-2.526a1.263 1.263 0 0 0 0 2.526");
}

</style>
