<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGS7aeSbdW)" class="r4i437pya"/><path class="i0htgpb1o"/></g><defs><linearGradient id="SVGS7aeSbdW" x1="19.04" x2="8.56" y1="5.412" y2="14.748" gradientUnits="userSpaceOnUse"><stop class="j7zeu_quw"/><stop offset="1" class="osubsuaxa"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:3ull-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i0htgpb1o {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.004 10.106c-.488-.944-2.153-.944-4.095-1.422c-1.549-.376-1.294-2.051-.967-2.838C4.385 6.222 4 7.104 4 7.897c0 2.838 3.513 3.16 4 3.624c.385.383.16.794 0 .958c-.385 1.128 1.01 1.942 1.818 2.256v2.051c0 .479.822 1.368 2.182 1.368s2.182-.889 2.182-1.368v-2.051c0-.478 2.305-1.313 1.818-2.256c-.386-.766-.16-.958 0-.958c1.942-.465 4-2.598 4-3.624c0-1.025-.364-1.709-1.818-2.05c.364.341.56 2.085-.604 2.837c-1.454.95-4.094.478-4.582 1.422c-.385.752-.16 2.209 0 2.838l1.673-.472c0 .95-.684 1.422-1.164 1.422c-.487 0-1.141.711-1.141 1.183c0 .479 0 1.368-.364 1.368s-.364-1.054-.364-1.368c0-.479-.363-1.183-1.134-1.183c-.778 0-1.004-.95-1.004-1.422l1.506.479c.32-.636.385-2.086 0-2.845");
}

.j7zeu_quw {
  stop-color: var(--svg-color--15493c, #15493c);
}

.osubsuaxa {
  stop-color: var(--svg-color--069a35, #069a35);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
