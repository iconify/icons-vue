<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="pczyxbb0k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ksm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pczyxbb0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.096 7.576c-.3-.27-.633-.473-1.033-.54c-.5-.068-1 .27-1.333.507c-.333.236-1 .845-1.266 1.08c-.267.238-.933.373-2.033 1.05c-1.1.675-5.365 3.447-5.365 3.447h1.1L4.2 15.722h.5l-.7.54c.4.102.8.035 1.166-.168v.169s5.899-2.366 7.032-1.758l-.7.204c.067 0 1.166.067 1.166.067c.067.473.333.912.734 1.15c.666.438.7.71.7.71s-.334.134-.334.337a3.03 3.03 0 0 1 1.9 0s-.034-.203-.5-.338a2.66 2.66 0 0 1-1.167-.946c-.266-.372-.366-.845-.2-1.285c.167-.44.734-.676 1.9-1.284c1.366-.71 1.7-1.25 1.866-1.69s.5-1.25.633-1.657c.133-.372.367-.676.667-.946a8 8 0 0 1 1.133-.507c.066.034-.667-.575-.9-.744");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
