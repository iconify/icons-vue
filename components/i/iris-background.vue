<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1c0MNdGb)" class="r4i437pya"/><path class="av7fnsw2l"/><path clip-rule="evenodd" class="hflzt6bip"/></g><defs><linearGradient id="SVG1c0MNdGb" x1="5.506" x2="18.248" y1="16.694" y2="9.212" gradientUnits="userSpaceOnUse"><stop class="b5d5li0go"/><stop offset=".34" class="mv-9cxbpf"/><stop offset=".69" class="a90pzubhc"/><stop offset="1" class="t5p8xpzfr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:iris-background" /></template>
<style>
.a90pzubhc {
  stop-color: var(--svg-color--ac4179, #ac4179);
}

.av7fnsw2l {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.202 4c-2.925.25-5 2.26-5.68 3.24l1.145-.1a6.98 6.98 0 0 1 4.19-2.295l.35-.845zm0 16c-2.925-.25-5.065-2.255-5.7-3.325l.93-.1c1.215 1.56 3.29 2.45 4.12 2.515zm1.61-16c2.9.2 4.925 2.225 5.685 3.295l-.94.13c-1.4-1.73-3.215-2.425-4.1-2.515zm0 16c2.9-.2 4.925-2.225 5.685-3.295l-1.115.095a7.04 7.04 0 0 1-4.21 2.34zm-8.11-4.695c-1.27-2.915-.53-5.645 0-6.64l.56.735a7.7 7.7 0 0 0-.1 4.89zm14.6 0c1.275-2.915.515-5.62-.015-6.62l-.44 1.02c.715 1.915.17 4.05-.115 4.85l.575.75z");
}

.b5d5li0go {
  stop-color: var(--svg-color--1190d4, #1190d4);
}

.ft5dv1b6b {
  fill: none;
}

.hflzt6bip {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m11.967 4.055l-1.46 3.325l-5.335.635l2.165 3.025l-2.165 4.97l3.665-.42l3.21 4.34l1.465-3.39l5.355-.61l-2.2-2.985l2.15-4.935l-3.65.38zm.19 1.674l-1.25 2.82a1 1 0 0 0-.07.375l3.026-.31l-1.37 3.31l1.27 1.726l1.185-2.616a1.9 1.9 0 0 0-.15-1.685c-.384-.592-1.72-2.383-2.47-3.392zm3.53 3.46l1.766-.205h.005l-1.37 3.196c-.07-.09-.28-.31-.535-.46c.235-.33.585-1.31.135-2.53m-5.574-.895l-3.45.39l1.1 1.5a2.77 2.77 0 0 1 2.23-1.16c0-.385.08-.65.12-.73m2.42 1.3l-2.965.33a1.68 1.68 0 0 0-1.265.986a521 521 0 0 0-1.785 4.1l2.765-.306c.14-.02.475-.08.66-.17l-1.8-2.475l3.55-.455zm-.74 2.856l-2.115.274q.849 1.18 1.71 2.35c.525.71 1.45.7 1.925.65l4.015-.485l-1.74-2.355a1.6 1.6 0 0 0-.39-.37l-1.225 2.776zm-1.97 3.03a3.7 3.7 0 0 0 .615-.23v.005a3.05 3.05 0 0 0 2.135 1.35l-.7 1.65z");
}

.mv-9cxbpf {
  stop-color: var(--svg-color--5060ae, #5060ae);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.t5p8xpzfr {
  stop-color: var(--svg-color--e0375c, #e0375c);
}

</style>
