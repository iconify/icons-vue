<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="zusyvccku"/><path class="khw7esb_m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dyp-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.khw7esb_m {
  fill: var(--svg-color--fffcff, #fffcff);
  d: path("M19.271 8.366a3.394 3.394 0 0 1-3.151 3.384v-.97a2.424 2.424 0 1 0-1.455-.315v1.072a3.4 3.4 0 0 1-1.212-.796V13.7h-.97V8.366a3.394 3.394 0 0 1 6.788 0m-4.412 3.239h.04v-1.6l.009.01V8.85h.97v7.272a3.393 3.393 0 0 1-6.449 1.479l.737-.766a2.424 2.424 0 0 0 4.722-.402h.01v-.068l.01-.243v-.005q.001-.144-.02-.29l-.01-.84a3.627 3.627 0 0 1-5.008.258a3.653 3.653 0 0 1-5.144-3.278c0-1.988 1.63-3.602 3.636-3.602v.97a2.667 2.667 0 1 0 .868 5.187a3.6 3.6 0 0 1-.625-2.23V7.881h.97v4.494a2.62 2.62 0 0 0 .494 1.673a2.662 2.662 0 0 0-.271-4.295V8.657c.465.199.885.493 1.231.863V6.426h.97v5.334h-.005a3.6 3.6 0 0 1-1.26 2.933a2.68 2.68 0 0 0 4.174-2.157v-.03c0-.063 0-.126-.01-.189v-.698z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zusyvccku {
  fill: var(--svg-color--ee1a20, #ee1a20);
  d: path("M16.313 16.754A7.02 7.02 0 0 0 19.24 10.6a4.122 4.122 0 0 0-4.3-6.06a7.03 7.03 0 0 0-9.445 4.494a4.121 4.121 0 0 0 1.736 6.924a7 7 0 0 0 1.794 1.333a.45.45 0 0 0-.058.47a3.88 3.88 0 0 0 7.34-1.003z");
}

</style>
