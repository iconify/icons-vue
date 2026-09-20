<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy6s9onvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:frin" /></template>
<style>
.qy6s9onvc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.552 3h14.896L18.04 8.586h-6.66v3.104h6.418l-1.21 4.965H11.38V21H4.552zm6.827 13.034h4.718l.906-3.724h-5.624zm-.62-4.344V8.43l-5.587-4.5v7.759zm-5.587.906v7.783h5.587v-3.873zm5.587 3.153V12.31h-4.91zM5.793 3.621h4.966v4.034zm5.586 4.345h6.189L18.64 3.62h-7.26z");
}

</style>
