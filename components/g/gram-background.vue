<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t-x-o3c6i"/><path clip-rule="evenodd" class="it6fffbde"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gram-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.it6fffbde {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.74 5.5H9.257c-.73 0-1.094 0-1.424.098c-.292.087-.563.23-.798.42c-.264.214-.46.51-.856 1.1l-1.74 2.61c-.26.39-.391.584-.426.79a1 1 0 0 0 .06.538c.08.194.25.358.591.686l6.472 6.232c.303.29.454.435.627.49a.8.8 0 0 0 .471 0c.175-.055.325-.2.627-.49l6.473-6.232c.34-.328.51-.492.591-.686a1 1 0 0 0 .06-.538c-.036-.206-.166-.4-.427-.79l-1.743-2.61c-.394-.591-.593-.887-.857-1.1a2.3 2.3 0 0 0-.797-.42c-.33-.097-.694-.097-1.424-.097M13.7 7.559a.27.27 0 0 1 .101-.127a.28.28 0 0 1 .316 0a.27.27 0 0 1 .101.127l.616 1.6a.36.36 0 0 0 .215.208l1.663.592a.3.3 0 0 1 .131.098a.26.26 0 0 1 0 .304a.3.3 0 0 1-.13.098l-1.664.592a.37.37 0 0 0-.215.208l-.616 1.6a.27.27 0 0 1-.1.127a.28.28 0 0 1-.317 0a.27.27 0 0 1-.101-.126l-.615-1.601a.35.35 0 0 0-.216-.208l-1.663-.592a.3.3 0 0 1-.13-.098a.26.26 0 0 1 0-.304a.3.3 0 0 1 .13-.098l1.663-.592a.37.37 0 0 0 .216-.208z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t-x-o3c6i {
  fill: var(--svg-color--30a1f5, #30a1f5);
  d: path("M24 0H0v24h24z");
}

</style>
