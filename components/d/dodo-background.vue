<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="nrxz2sjfm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dodo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.nrxz2sjfm {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.419 5.535c-.264.546-.005 1.144.367 1.628c-4.833.706-5.675 5.238-5.845 7.897h1.883c.112-2.353 1.223-5.897 5.167-5.897s5.058 3.544 5.167 5.897h1.882c.15-2.405-.687-7.03-5.36-7.86c.25-.592.424-1.42.146-1.665c-.33-.296-.706.047-.857.25c-.023-.537-.226-1.6-.814-1.549c-.593.057-.767 1.13-.776 1.666c-.48-.734-.838-.55-.96-.367m-.301 6.701a.47.47 0 1 1 .94 0v.47a.47.47 0 1 1-.94 0zm3.294-.47c-.259 0-.47.178-.47.4v.611c0 .222.211.4.47.4s.47-.178.47-.4v-.611c0-.222-.211-.4-.47-.4M5.472 16H4v3.765h1.473c1.007 0 1.821-.847 1.821-1.883C7.294 16.847 6.48 16 5.473 16m-.22.941h-.31v1.883h.31c.597 0 1.1-.325 1.1-.942c0-.616-.503-.94-1.1-.94m7.219-.941h1.473c1.007 0 1.82.847 1.82 1.882c0 1.036-.813 1.883-1.82 1.883H12.47zm.94.941h.311c.598 0 1.101.325 1.101.941c0 .617-.503.942-1.1.942h-.311zm-3.764 2.824a1.882 1.882 0 1 0 0-3.765a1.882 1.882 0 0 0 0 3.765m0-.941a.941.941 0 1 0 0-1.883a.941.941 0 0 0 0 1.883M20 17.883a1.882 1.882 0 1 1-3.764 0a1.882 1.882 0 0 1 3.764 0m-.941 0a.941.941 0 1 1-1.882 0a.941.941 0 0 1 1.882 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
