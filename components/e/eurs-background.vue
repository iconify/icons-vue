<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGeX70vdLc)" class="r4i437pya"/><path class="apj_79btu"/></g><defs><linearGradient id="SVGeX70vdLc" x1="19.462" x2="4.834" y1="4.999" y2="18.235" gradientUnits="userSpaceOnUse"><stop class="yacl3vbcn"/><stop offset=".464" class="f3prw0a_k"/><stop offset="1" class="u8qw5jg4g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eurs-background" /></template>
<style>
.apj_79btu {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.722 17.592A7.98 7.98 0 0 0 20 12a7.99 7.99 0 0 0-3.062-6.295l-1.433.055c-2.112.241-3.975 1.464-4.904 3.238H18.5l-1 2h-7.495l-.005.046c-.097.77-.087 1.184 0 1.904l.006.052H16.5l-1 2h-4.735c.822 1.186 2.206 1.98 3.781 2.25c1.356.232 2.471.314 3.175.341m-2.314 1.648A8 8 0 0 1 4 12a8 8 0 0 1 9.815-7.793a7.54 7.54 0 0 0-5.396 4.791H7l-1 2h2V11c-.06.808-.053 1.242 0 2H7l-1 2h2.56c1.158 2.33 3.829 3.892 5.986 4.148q.459.055.863.091");
}

.f3prw0a_k {
  stop-color: var(--svg-color--2b7fef, #2b7fef);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u8qw5jg4g {
  stop-color: var(--svg-color--15bcff, #15bcff);
}

.yacl3vbcn {
  stop-color: var(--svg-color--b030ec, #b030ec);
}

</style>
