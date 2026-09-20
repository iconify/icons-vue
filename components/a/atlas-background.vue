<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mpdm1mbck"/><path class="fjovwybcq"/><path class="gzfb3w39w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atlas-background" /></template>
<style>
.fjovwybcq {
  fill: var(--svg-color--000, #000);
  d: path("m12 9.028l-3.246 7.347c-.105.233-.165.425-.398.425H6.207c-.306 0-.475-.087-.32-.425l5.24-12.028c.104-.2.173-.347.41-.347h.929c.233 0 .297.146.411.347l5.239 12.023c.15.343-.023.43-.33.43h-2.143c-.233 0-.297-.192-.398-.425L12 9.024z");
}

.ft5dv1b6b {
  fill: none;
}

.gzfb3w39w {
  fill: var(--svg-color--000, #000);
  d: path("M12.004 20L9.86 15.886h4.215z");
}

.mpdm1mbck {
  fill: var(--svg-color--3ff, #3ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
