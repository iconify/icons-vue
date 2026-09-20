<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7yC2zezO)" class="r4i437pya"/><path class="xs_2g5apd"/></g><defs><linearGradient id="SVG7yC2zezO" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="fvudeob7i"/><stop offset="1" class="jukqthmaq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arsw-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fvudeob7i {
  stop-color: var(--svg-color--00ebe4, #00ebe4);
}

.jukqthmaq {
  stop-color: var(--svg-color--009ef8, #009ef8);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xs_2g5apd {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.774 18.132L5.548 20C6.994 15.303 10.194 9.332 12 6.4c1.806 2.932 5.42 9.332 6.451 13.6l.775-1.869C18.813 16 14.839 6.932 12 4C9.42 6.932 5.806 15.112 4.774 18.131M12 12c-1.239 1.92-2.926 6.131-3.613 8l-.774-2.132C8.129 16 10.71 10.932 12 9.068c1.548 1.864 4.129 7.2 4.387 8.8l-.774 1.864c-.516-1.6-2.323-5.6-3.613-7.732m-.774 7.468L12 18.4l.774 1.068l.774-1.068c0-.8-1.032-2.668-1.548-3.2c-.516.532-1.548 2.56-1.548 3.2z");
}

</style>
