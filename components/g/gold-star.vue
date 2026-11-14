<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyg942bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gold-star" /></template>
<style>
.gyg942bzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.102 7.483l.75 1.69a1.5 1.5 0 0 0 1.216.883l1.838.191a1.206 1.206 0 0 1 .681 2.096l-1.375 1.236a1.5 1.5 0 0 0-.464 1.429l.386 1.807a1.206 1.206 0 0 1-1.783 1.296l-1.599-.926a1.5 1.5 0 0 0-1.504 0l-1.599.926a1.206 1.206 0 0 1-1.783-1.296l.386-1.807a1.5 1.5 0 0 0-.464-1.429l-1.375-1.236a1.206 1.206 0 0 1 .681-2.096l1.838-.191a1.5 1.5 0 0 0 1.216-.883l.75-1.69a1.206 1.206 0 0 1 2.204 0M19.5 2.5V6m-1.75-1.75h3.5");
}

</style>
