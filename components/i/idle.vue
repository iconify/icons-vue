<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt9_8_ujb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idle" /></template>
<style>
.gt9_8_ujb {
  fill: var(--svg-color--1b14dc, #1b14dc);
  d: path("M11.5 18V3l-6 3.55V18zm7-12h-6v15l6-3.55z");
}

</style>
