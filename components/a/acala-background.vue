<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGDhaJPcBU)" class="r4i437pya"/><path clip-rule="evenodd" class="fyye-2xut"/></g><defs><linearGradient id="SVGDhaJPcBU" x1="19.102" x2="7.298" y1="20" y2="5.42" gradientUnits="userSpaceOnUse"><stop class="mamuo5b0r"/><stop offset=".524" class="vtoc0-r2p"/><stop offset="1" class="v28ua0nqc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:acala-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fyye-2xut {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m.033-.751a7.249 7.249 0 1 0 0-14.498a7.249 7.249 0 0 0 0 14.498M12 18.694a6.694 6.694 0 1 0 0-13.388a6.694 6.694 0 0 0 0 13.388m.016-.816a5.894 5.894 0 1 0 0-11.788a5.894 5.894 0 0 0 0 11.788m-.332-10.656l4.267 7.402l.457-.794l-3.81-6.608zm-4.092 6.595l3.652-6.336l.007.013l.008-.012l4.327 7.508h-.915l-1.093-1.897a5.2 5.2 0 0 0-1.575-.242q-.425 0-.827.06l.527-.913a6 6 0 0 1 1.285.072l-1.737-3.014l-3.202 5.555zm2.483-.096l1.64-2.847l-.457-.794l-2.83 4.91h.915l.009-.015c.784-.473 1.685-.712 2.669-.712c.628 0 1.23.111 1.787.315l-.613-1.062a6.1 6.1 0 0 0-3.12.205");
}

.mamuo5b0r {
  stop-color: var(--svg-color--5a81ff, #5a81ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v28ua0nqc {
  stop-color: var(--svg-color--ff4c3b, #ff4c3b);
}

.vtoc0-r2p {
  stop-color: var(--svg-color--e40c5b, #e40c5b);
}

</style>
