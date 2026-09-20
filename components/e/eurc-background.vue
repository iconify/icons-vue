<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><mask id="SVGCcwNndIU" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="beaf9ac8r"/></mask><g mask="url(#SVGCcwNndIU)"><path class="eokb-tbaq"/></g><path class="l3jjk6b3c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eurc-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.eokb-tbaq {
  fill: var(--svg-color--0b53bf, #0b53bf);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.l3jjk6b3c {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a8 8 0 1 1 0 16a8 8 0 0 1 0-16m-1.44 2.175A5.99 5.99 0 0 0 6 12c0 2.82 1.94 5.185 4.56 5.825v-1.03a5.008 5.008 0 0 1 0-9.59zm2.88 1.03A5.01 5.01 0 0 1 17 12a5.01 5.01 0 0 1-3.56 4.795v1.03A5.99 5.99 0 0 0 18 12c0-2.82-1.94-5.185-4.56-5.825zM12.62 9c-1.17 0-2.354.654-2.782 1.925H9.07v.75h.614a4 4 0 0 0 0 .65H9.07v.75h.768C10.266 14.345 11.45 15 12.62 15c.485 0 .97-.11 1.4-.335l-.32-.76c-.35.14-.73.22-1.094.22c-.723 0-1.405-.308-1.731-1.05h1.59l.31-.75H10.69a3.4 3.4 0 0 1 0-.65h2.35l.31-.75h-2.475c.326-.742 1.008-1.05 1.73-1.05c.365 0 .745.08 1.095.22l.32-.76A3 3 0 0 0 12.62 9");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
