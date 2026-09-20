<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="l7yl2dbjc"/><path class="uo78mfi4z"/><path class="iwsv_wbwi"/><path fill="url(#SVGc4AmHnjD)" class="e9zouebzy"/><path class="xj-800bbc"/><path class="rbp6-6bgq"/></g><defs><linearGradient id="SVGc4AmHnjD" x1="4.001" x2="20.308" y1="11.385" y2="11.385" gradientUnits="userSpaceOnUse"><stop class="k827ibcbc"/><stop offset=".2" class="w0k8ahbcl"/><stop offset=".54" class="we2yf3b-w"/><stop offset="1" class="eduq_71-i"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ben-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.e9zouebzy {
  d: path("M12 18c3.59 0 6.5-2.798 6.5-6.25S15.59 5.5 12 5.5s-6.5 2.798-6.5 6.25S8.41 18 12 18");
}

.eduq_71-i {
  stop-color: var(--svg-color--e95e1b, #e95e1b);
}

.ft5dv1b6b {
  fill: none;
}

.iwsv_wbwi {
  fill: var(--svg-color--e2e3e9, #e2e3e9);
  d: path("M12 18.02c3.59 0 6.5-2.81 6.5-6.27S15.59 5.48 12 5.48s-6.5 2.81-6.5 6.27s2.91 6.27 6.5 6.27m0 .48c3.865 0 7-3.02 7-6.75S15.865 5 12 5c-3.864 0-7 3.02-7 6.75s3.136 6.75 7 6.75");
}

.k827ibcbc {
  stop-color: var(--svg-color--6d7ace, #6d7ace);
}

.l7yl2dbjc {
  fill: var(--svg-color--3b5169, #3b5169);
  d: path("M12 20c4.418 0 8-3.365 8-7.515S16.418 4.97 12 4.97s-8 3.365-8 7.515S7.582 20 12 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rbp6-6bgq {
  fill: var(--svg-color--e3e3e3, #e3e3e3);
  d: path("M11 9.336v1.7l.75.48l.75-.725V9.336H14l-2.5-3.15l-2 3.15zm1 8.15L11 17c-.4-4.075 2.165-5.89 3.5-6.21l-.25-.97l3.5 1.45L15 13.456l-.25-.97C12.95 13.26 12.835 15.87 13 17zm-1-5.245l-1.5.97c-.2-.19-.585-.24-.75-.24l-.25 1.21l-2.75-2.665l3.5-1.45l-.25 1.21c1 0 1.75.645 2 .965");
}

.uo78mfi4z {
  fill: var(--svg-color--6389b0, #6389b0);
  d: path("M12 19.52c4.418 0 8-3.475 8-7.76S16.418 4 12 4s-8 3.474-8 7.76s3.582 7.76 8 7.76");
}

.w0k8ahbcl {
  stop-color: var(--svg-color--9971a3, #9971a3);
}

.we2yf3b-w {
  stop-color: var(--svg-color--ca6664, #ca6664);
}

.xj-800bbc {
  fill: var(--svg-color--7d7f7c, #7d7f7c);
  d: path("M9.5 9.5v-.166H11V9.5zm3 0v-.166H14V9.5zM11 11.273v-.245l.75.485l.75-.725v.24l-.75.73zM9.5 10.3l-.25-.24L9 11.274h.25l.25-.97zm-1 3.88l-2.75-2.665v.245l2.85 2.665l.25-1.215l.65.245l1.5-.97v-.245l-1.5.97c-.2-.19-.585-.24-.75-.24zm2.5 3.06V17l1 .485L13 17c-.165-.97-.25-3.79 1.75-4.515l.25.24c-1.25.44-2.2 2.14-2 4.275v.24l-1 .485zm6.75-5.725v-.24L15 13.45v.24l2.75-2.18z");
}

</style>
