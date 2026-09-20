<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGnzO48b2M" x1="0%" x2="115.015%" y1="50%" y2="50%"><stop offset="0%" class="owkqslb_v"/><stop offset="15%" class="gf4z04bvt"/><stop offset="28%" class="y1yyj9bgl"/><stop offset="42%" class="fj-8fibyz"/><stop offset="54%" class="tth4ambmf"/><stop offset="67%" class="p8_zs4bkg"/><stop offset="79%" class="kw_2z77qb"/><stop offset="91%" class="qnmirob6z"/><stop offset="100%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVGMTc1AcLj" x1="53.816%" x2="43.444%" y1="17.257%" y2="151.488%"><stop offset="9%" class="z65hc5b4d"/><stop offset="90%" class="rwcjds48k"/></linearGradient><linearGradient id="SVG0ouq0BHD" x1="93.049%" x2="-9.597%" y1="9.981%" y2="113.191%"><stop offset="9%" class="z65hc5b4d"/><stop offset="90%" class="rwcjds48k"/></linearGradient><linearGradient id="SVG3JQhzesp" x1="32.388%" x2="91.688%" y1="46.039%" y2="52.244%"><stop offset="9%" class="z65hc5b4d"/><stop offset="90%" class="rwcjds48k"/></linearGradient></defs><path fill="url(#SVGnzO48b2M)" class="qr_yrkb-w"/><path fill="url(#SVGMTc1AcLj)" class="cj7hice-b"/><path fill="url(#SVG0ouq0BHD)" class="myg-82bbb"/><path fill="url(#SVG3JQhzesp)" class="zdalf9qcg"/><path class="wj8kk3bmp"/><path class="kktezlbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:clion" /></template>
<style>
.cj7hice-b {
  d: path("M92.027 100.107L97.573 0l-73.92 46.587L0 188.213z");
}

.fj-8fibyz {
  stop-color: var(--svg-color--de4a8c, #de4a8c);
}

.gf4z04bvt {
  stop-color: var(--svg-color--fb348c, #fb348c);
}

.kktezlbqm {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.947 177.76h60v10h-60zm60.186-109.92h13.334v49.04h26.266V128h-39.6zM63.676 98.815l.004-.655a30.773 30.773 0 0 1 31.547-31.307a31.23 31.23 0 0 1 23.84 9.334l-8.4 9.786a22.35 22.35 0 0 0-15.494-6.826c-10.073 0-17.356 8.266-17.517 18.481l-.003.532c0 10.373 7.174 19.013 17.52 19.013c6.934 0 11.147-2.666 16-7.093l8.32 8.587a30.93 30.93 0 0 1-24.826 10.666a30.533 30.533 0 0 1-30.99-30.518");
}

.kw_2z77qb {
  stop-color: var(--svg-color--79958a, #79958a);
}

.myg-82bbb {
  d: path("M250.907 76.72L217.973 9.76l-62.186 22.507l-63.76 67.84L0 188.213l83.013 60.427l104.347-94.107z");
}

.owkqslb_v {
  stop-color: var(--svg-color--ff318c, #ff318c);
}

.p8_zs4bkg {
  stop-color: var(--svg-color--a2778b, #a2778b);
}

.qnmirob6z {
  stop-color: var(--svg-color--49b98a, #49b98a);
}

.qr_yrkb-w {
  d: path("M92.027 100.107L97.573 0l58.214 32.267z");
}

.rwcjds48k {
  stop-color: var(--svg-color--009ae5, #009ae5);
}

.tth4ambmf {
  stop-color: var(--svg-color--c45d8b, #c45d8b);
}

.wj8kk3bmp {
  d: path("M48 48h160v160H48z");
}

.y1yyj9bgl {
  stop-color: var(--svg-color--f03c8c, #f03c8c);
}

.z65hc5b4d {
  stop-color: var(--svg-color--21d789, #21d789);
}

.zdalf9qcg {
  d: path("M208 146.773V208H107.467l44.186 34.187l64 13.813L256 164.667z");
}

</style>
