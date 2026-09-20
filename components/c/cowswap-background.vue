<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e4rhb8bew"/><path clip-rule="evenodd" class="sd8xvdbhb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cowswap-background" /></template>
<style>
.e4rhb8bew {
  fill: var(--svg-color--004293, #004293);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sd8xvdbhb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.068 17.333a1.78 1.78 0 0 1-1.7-1.24L7.16 12.296h-.742a1.78 1.78 0 0 1-1.7-1.24L4 8.8h2.692l-1.42-2.133h13.456L17.308 8.8H20l-.718 2.256a1.78 1.78 0 0 1-1.7 1.24h-.742l-1.209 3.797a1.78 1.78 0 0 1-1.7 1.24zm-.912-6.074c0 .573.428 1.037.958 1.037c.529 0 .958-.464.958-1.037c0-.572-.43-1.037-.958-1.037c-.53 0-.958.465-.958 1.037m5.688 0c0 .573-.428 1.037-.958 1.037c-.529 0-.958-.464-.958-1.037c0-.572.43-1.037.958-1.037c.53 0 .958.465.958 1.037");
}

</style>
