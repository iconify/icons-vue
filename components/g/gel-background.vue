<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGu1gkobUm)" class="r4i437pya"/><path class="qid8x0bdp"/><path class="atkntnbti"/></g><defs><linearGradient id="SVGu1gkobUm" x1="14.287" x2="14.287" y1="9.737" y2="19.998" gradientUnits="userSpaceOnUse"><stop class="ozqlykbuu"/><stop offset="1" class="tshln8pzh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gel-background" /></template>
<style>
.atkntnbti {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.543 10.711c0-.1.06-.183.15-.22l.129-.045c.844-.333 1.726-.56 2.626-.677a7.4 7.4 0 0 1 2.155.114a.536.536 0 0 1 .43.55a.6.6 0 0 1-.069.26l-5.252 9.204a.19.19 0 0 1-.169.1z");
}

.ft5dv1b6b {
  fill: none;
}

.ozqlykbuu {
  stop-color: var(--svg-color--ffc4a4, #ffc4a4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qid8x0bdp {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.319 8.654c0 .22-.206.375-.43.352a7.3 7.3 0 0 0-1.519 0c-1.025.105-1.875.448-2.658.741l-.142.05c-.832.311-1.6.572-2.511.595a5.3 5.3 0 0 1-1.185-.11a.96.96 0 0 1-.737-.755a4.634 4.634 0 1 1 9.182-.878zm-8.811 2.3a.45.45 0 0 0-.483.215a.5.5 0 0 0-.057.178a.4.4 0 0 0 .046.21l4.355 8.34c.073.137.27.137.343 0l5.252-9.204a.6.6 0 0 0 .068-.302a.53.53 0 0 0-.43-.508a7.4 7.4 0 0 0-2.155-.114c-.924.096-1.692.38-2.488.677l-.124.046a8.3 8.3 0 0 1-2.758.64a5.8 5.8 0 0 1-1.57-.183z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tshln8pzh {
  stop-color: var(--svg-color--fe858c, #fe858c);
}

</style>
