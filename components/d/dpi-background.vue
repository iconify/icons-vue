<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="submdjbwb"/><path class="un229sbad"/><path class="cmgi2sbkb"/><path class="baura3bgd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dpi-background" /></template>
<style>
.baura3bgd {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.837 12.282c.53 0 1.091-.087 1.562-.215c.435-.13.84-.346 1.19-.636a2.76 2.76 0 0 0 .828-1.027c.207-.422.308-.93.308-1.533c0-.594-.09-1.054-.27-1.483a2.66 2.66 0 0 0-.754-1.031a3.4 3.4 0 0 0-1.174-.648a5 5 0 0 0-1.408-.203H6.36v6.776zM4.855 4h3.78q.948-.002 1.83.301q.88.295 1.558.907c.466.43.836.953 1.084 1.536c.285.672.424 1.398.407 2.127q0 1.261-.467 2.184c-.29.59-.7 1.112-1.205 1.532c-.487.4-1.043.706-1.641.903c-.603.2-1.002.298-1.582.298H4.856z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cmgi2sbkb {
  fill: var(--svg-color--9b74ec, #9b74ec);
  d: path("M14.255 8.111a4.55 4.55 0 0 0-1.039-1.566a4.2 4.2 0 0 0-1.833-1.039c.428.701.667 1.502.693 2.323c.248.252.49 2.214.64 2.59l-4.721 3.26v-.84c-.546.046-1.084 0-1.634-.007v2.462h3.422a5.05 5.05 0 0 0 3.26-1.227a4.7 4.7 0 0 0 1.152-1.559c.313-.7.466-1.461.448-2.228c0-.851-.128-1.544-.388-2.169");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.submdjbwb {
  fill: var(--svg-color--3c176b, #3c176b);
  d: path("M19.141 12.52L11.64 5.11l-4.278-.8l-2.503 9.45l6.32 6.24a10.57 10.57 0 0 0 7.966-7.48z");
}

.un229sbad {
  fill: var(--svg-color--6b42bd, #6b42bd);
  d: path("M8.243 12.93V7.012h1.318c.455.004.907.076 1.34.215c.46.15.878.406 1.22.749c.003-.79-.283-1.581-.69-2.297a5 5 0 0 0-1.384-.192H6.36v7.435c.542.008 1.34.053 1.882.008");
}

</style>
