<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bta_82cvz"/><path class="pc71ewbwa"/><path class="io3jjc2xi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:jst-background" /></template>
<style>
.bta_82cvz {
  fill: var(--svg-color--b41514, #b41514);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.io3jjc2xi {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.47 4.47c.179 3.928 3.482 7.06 7.53 7.06s7.351-3.132 7.53-7.06h-2.369c-.24 2.588-2.46 4.615-5.16 4.615s-4.92-2.027-5.16-4.615z");
}

.pc71ewbwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.882 5.882a1.882 1.882 0 1 1-3.764 0a1.882 1.882 0 0 1 3.764 0m0 12.236a1.882 1.882 0 1 1-3.764 0a1.882 1.882 0 0 1 3.764 0M4.94 12.94h14.12v2.353H4.94z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
