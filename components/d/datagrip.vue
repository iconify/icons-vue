<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGdb8Zxebq" x1="48.681%" x2="50.185%" y1="46.207%" y2="99.477%"><stop offset="16%" class="z65hc5b4d"/><stop offset="54%" class="wwhk21bzd"/><stop offset="100%" class="gp61sbbkt"/></linearGradient><linearGradient id="SVGGOgt5dhQ" x1="37.375%" x2="53.526%" y1="64.021%" y2="50%"><stop offset="0%" class="gp61sbbkt"/><stop offset="95%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVG4RfsVdOI" x1="34.806%" x2="45.581%" y1="22.767%" y2="53.89%"><stop offset="0%" class="gp61sbbkt"/><stop offset="2%" class="u4ccy6bml"/><stop offset="28%" class="j2rircicc"/><stop offset="51%" class="vr-szex7q"/><stop offset="69%" class="dwaghvbrv"/><stop offset="80%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVGZGFS0drK" x1="8.271%" x2="124.62%" y1="28.102%" y2="74.034%"><stop offset="8%" class="z65hc5b4d"/><stop offset="89%" class="gp61sbbkt"/></linearGradient><linearGradient id="SVGa1axsdMd" x1="7.221%" x2="101.291%" y1="50%" y2="50%"><stop offset="31%" class="z65hc5b4d"/><stop offset="49%" class="xjkblsbfx"/><stop offset="77%" class="v1-n43bey"/><stop offset="100%" class="tt1l_5beu"/></linearGradient></defs><path fill="url(#SVGdb8Zxebq)" class="gjpkrobxt"/><path fill="url(#SVGGOgt5dhQ)" class="nzjkzy0mm"/><path fill="url(#SVG4RfsVdOI)" class="tyznxdqjw"/><path fill="url(#SVGZGFS0drK)" class="v6ifhr6_o"/><path fill="url(#SVGa1axsdMd)" class="p_2dhmx3h"/><path class="w1_a55bdg"/><path class="k4p6srb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:datagrip" /></template>
<style>
.dwaghvbrv {
  stop-color: var(--svg-color--26ce91, #26ce91);
}

.gjpkrobxt {
  d: path("m239.68 39.787l16.32 104.8l-30.16 17.546z");
}

.gp61sbbkt {
  stop-color: var(--svg-color--6b57ff, #6b57ff);
}

.j2rircicc {
  stop-color: var(--svg-color--4a91ca, #4a91ca);
}

.k4p6srb5z {
  fill: var(--svg-color--fff, #fff);
  d: path("M64.24 68.48h25.84c20.592 0 34.911 14.009 35.196 32.375l.004.745c0 18.667-14.4 33.12-35.2 33.12H64.24zM78.8 81.627v40h11.28a18.88 18.88 0 0 0 19.947-19.787v-.24A19.013 19.013 0 0 0 90.08 81.627zm49.067 20.16v-.187a34 34 0 0 1 34.666-34.267a36.35 36.35 0 0 1 26.027 9.094l-9.173 11.066a24.48 24.48 0 0 0-16.848-6.724l-.459.004c-10.554 0-18.863 9.19-19.037 20.286l-.003.541c0 12.107 8.347 21.013 20.08 21.013a23.28 23.28 0 0 0 13.76-3.946v-9.494h-14.667V96.587h28.774v28.773a42.9 42.9 0 0 1-28.294 10.507c-20.64 0-34.826-14.534-34.826-34.08M62.72 177.653h60v10h-60z");
}

.nzjkzy0mm {
  d: path("M239.68 39.787L148.027 0l-25.574 21.227z");
}

.p_2dhmx3h {
  d: path("M0 1.813V118.16l222.16 76.347l17.52-154.72z");
}

.tt1l_5beu {
  stop-color: var(--svg-color--ff45ed, #ff45ed);
}

.tyznxdqjw {
  d: path("M172.987 256L30.773 142.693l-28.56 85.894z");
}

.u4ccy6bml {
  stop-color: var(--svg-color--685cfb, #685cfb);
}

.v1-n43bey {
  stop-color: var(--svg-color--b74af7, #b74af7);
}

.v6ifhr6_o {
  d: path("M192.8 184.4L0 118.16L172.987 256z");
}

.vr-szex7q {
  stop-color: var(--svg-color--34b7a7, #34b7a7);
}

.w1_a55bdg {
  d: path("M48 47.68h160v160H48z");
}

.wwhk21bzd {
  stop-color: var(--svg-color--419fbc, #419fbc);
}

.xjkblsbfx {
  stop-color: var(--svg-color--59a3b2, #59a3b2);
}

.z65hc5b4d {
  stop-color: var(--svg-color--21d789, #21d789);
}

</style>
