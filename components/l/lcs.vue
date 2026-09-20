<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bwy-z2bui"/><path fill="url(#SVGocDZfeTk)" class="sbb3uo2rk"/><path fill="url(#SVGkVqmKbnI)" clip-rule="evenodd" class="mi457ibqa"/><path fill="url(#SVGIv0boeSA)" class="biew_xbbd"/><path fill="url(#SVGI0DiQeeb)" clip-rule="evenodd" class="c6huh4cck"/><defs><linearGradient id="SVGocDZfeTk" x1="12" x2="12" y1="8.175" y2="15.825" gradientUnits="userSpaceOnUse"><stop offset=".146" class="cn4gzf0bk"/><stop offset=".615" class="gitfzu-wk"/></linearGradient><linearGradient id="SVGkVqmKbnI" x1="11.999" x2="11.999" y1="8.175" y2="15.827" gradientUnits="userSpaceOnUse"><stop class="njedkvbnv"/><stop offset=".776" class="hl0kztbtm"/></linearGradient><linearGradient id="SVGIv0boeSA" x1="12" x2="12" y1="15.824" y2="8.174" gradientUnits="userSpaceOnUse"><stop class="b_z5fxbey"/><stop offset="1" class="gu9vvmvyg"/></linearGradient><linearGradient id="SVGI0DiQeeb" x1="17.618" x2="17.618" y1="10.393" y2="8.174" gradientUnits="userSpaceOnUse"><stop class="whu75ubce"/><stop offset=".743" class="y68-j0b-d"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lcs" /></template>
<style>
.b_z5fxbey {
  stop-color: var(--svg-color--db9d16, #db9d16);
}

.biew_xbbd {
  d: path("M15.022 15.479a.86.86 0 0 0 1.378 0l4.43-5.951a.853.853 0 0 0-.53-1.347a.6.6 0 0 0-.309.043l-2.423.934a5.17 5.17 0 0 1-3.715 0l-2.423-.934a.6.6 0 0 0-.309-.043a.853.853 0 0 0-.53 1.347z");
}

.bwy-z2bui {
  fill: var(--svg-color--c4c4c4, #c4c4c4);
  d: path("M7.6 8.52a.86.86 0 0 1 1.378 0l4.43 5.951a.853.853 0 0 1-.53 1.347a.6.6 0 0 1-.308-.043l-2.424-.934a5.17 5.17 0 0 0-3.714 0l-2.424.934a.6.6 0 0 1-.309.043a.853.853 0 0 1-.529-1.347z");
}

.c6huh4cck {
  fill-rule: evenodd;
  d: path("m20.629 9.797l.2-.27a.853.853 0 0 0-.529-1.346a.6.6 0 0 0-.309.043l-2.423.934a5.17 5.17 0 0 1-3.304.138l-.028.014c1.74.657 5.412 1.677 6.261.64q.07-.085.132-.153");
}

.cn4gzf0bk {
  stop-color: var(--svg-color--283da8, #283da8);
}

.ft5dv1b6b {
  fill: none;
}

.gitfzu-wk {
  stop-color: var(--svg-color--4196f9, #4196f9);
}

.gu9vvmvyg {
  stop-color: var(--svg-color--e2da20, #e2da20);
}

.hl0kztbtm {
  stop-color: var(--svg-color--4171f9, #4171f9);
}

.mi457ibqa {
  fill-rule: evenodd;
  d: path("m13.208 14.203l.2.27a.853.853 0 0 1-.53 1.346a.6.6 0 0 1-.308-.043l-2.424-.934a5.17 5.17 0 0 0-3.303-.139l-.029-.013c1.74-.657 5.413-1.677 6.262-.64q.07.085.132.153");
}

.njedkvbnv {
  stop-color: var(--svg-color--283eaa, #283eaa);
}

.sbb3uo2rk {
  d: path("M7.6 8.52a.86.86 0 0 1 1.378 0l4.43 5.951a.853.853 0 0 1-.53 1.347a.6.6 0 0 1-.308-.043l-2.424-.934a5.17 5.17 0 0 0-3.714 0l-2.424.934a.6.6 0 0 1-.309.043a.853.853 0 0 1-.529-1.347z");
}

.whu75ubce {
  stop-color: var(--svg-color--e0a500, #e0a500);
}

.y68-j0b-d {
  stop-color: var(--svg-color--eccd3c, #eccd3c);
}

</style>
