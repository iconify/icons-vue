<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="aokk0qrfy"/><path class="mk__gfm9b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coinex-background" /></template>
<style>
.aokk0qrfy {
  fill: var(--svg-color--0ead98, #0ead98);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.mk__gfm9b {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.238 20C7.695 20 4 16.41 4 12s3.695-8 8.238-8c3.156 0 6.071 1.788 7.434 4.55l.328.664l-2.303 2.235l-1.534-1.468l1.196-1.162c-1.108-1.68-3.044-2.734-5.121-2.734c-3.347 0-6.072 2.654-6.072 5.91s2.725 5.91 6.072 5.91c2.078 0 4.013-1.053 5.12-2.733l-4.199-4.085a1.3 1.3 0 0 0-.921-.372a1.32 1.32 0 0 0-.922.372a1.25 1.25 0 0 0 0 1.807c.245.24.574.372.922.372s.671-.132.921-.372l.372-.367l1.54 1.468l-.378.367a3.5 3.5 0 0 1-2.455.989a3.5 3.5 0 0 1-2.455-.989a3.294 3.294 0 0 1 0-4.748a3.5 3.5 0 0 1 2.455-.988c.926 0 1.798.353 2.455.988L20 14.772l-.328.663C18.309 18.212 15.389 20 12.238 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
