<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG2m3AVb6p" x1="4.494" x2="13.832" y1="-1712.086" y2="-1695.914" gradientTransform="translate(0 1720)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cd1ml4_iw"/><stop offset=".5" class="uu95pmbwl"/><stop offset="1" class="syyrs4-qo"/></linearGradient></defs><path class="zfsckybdy"/><path class="nt-j8xbdv"/><path class="iseexzbet"/><path class="x15jyjbnr"/><path class="hxq6byb8p"/><path class="nlwaukbxo"/><path class="eahst6kvs"/><path class="bt891s5nl"/><path fill="url(#SVG2m3AVb6p)" class="lugf9nb5a"/><path class="n6dtqjluy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-word" /></template>
<style>
.bt891s5nl {
  d: path("M15.132 8.85h-6.62V23.8h6.62a1.2 1.2 0 0 0 1.194-1.191V10.041a1.2 1.2 0 0 0-1.194-1.191");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cd1ml4_iw {
  stop-color: var(--svg-color--2368c4, #2368c4);
}

.eahst6kvs {
  d: path("M15.783 8.85H8.512V23.8h7.271a1.2 1.2 0 0 0 1.194-1.191V10.041a1.2 1.2 0 0 0-1.194-1.191");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hxq6byb8p {
  d: path("M16.434 8.2H8.512v16.25h7.922a1.2 1.2 0 0 0 1.194-1.191V9.391A1.2 1.2 0 0 0 16.434 8.2");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.iseexzbet {
  fill: var(--svg-color--185abd, #185abd);
  d: path("M8.512 16v6.5l10.418 1.3L30 22.5V16Z");
}

.lugf9nb5a {
  d: path("M3.194 8.85h11.938a1.193 1.193 0 0 1 1.194 1.191v11.918a1.193 1.193 0 0 1-1.194 1.191H3.194A1.19 1.19 0 0 1 2 21.959V10.041A1.19 1.19 0 0 1 3.194 8.85");
}

.n6dtqjluy {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.9 17.988q.035.276.046.481h.028q.015-.195.065-.47c.05-.275.062-.338.089-.465l1.255-5.407h1.624l1.3 5.326a8 8 0 0 1 .162 1h.022a8 8 0 0 1 .135-.975l1.039-5.358h1.477l-1.824 7.748h-1.727l-1.237-5.126q-.054-.222-.122-.578t-.084-.52h-.021q-.021.189-.084.561t-.1.552L7.78 19.871H6.024L4.19 12.127h1.5l1.131 5.418a5 5 0 0 1 .079.443");
}

.nlwaukbxo {
  d: path("M15.783 8.85H8.512V25.1h7.271a1.2 1.2 0 0 0 1.194-1.191V10.041a1.2 1.2 0 0 0-1.194-1.191");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nt-j8xbdv {
  fill: var(--svg-color--2b7cd3, #2b7cd3);
  d: path("M30 9.5H8.512V16l11.069 1.95L30 16Z");
}

.syyrs4-qo {
  stop-color: var(--svg-color--1146ac, #1146ac);
}

.uu95pmbwl {
  stop-color: var(--svg-color--1a5dbe, #1a5dbe);
}

.x15jyjbnr {
  fill: var(--svg-color--103f91, #103f91);
  d: path("M9.705 29h19.1A1.19 1.19 0 0 0 30 27.809V22.5H8.512v5.309A1.19 1.19 0 0 0 9.705 29");
}

.zfsckybdy {
  fill: var(--svg-color--41a5ee, #41a5ee);
  d: path("M28.806 3H9.705a1.19 1.19 0 0 0-1.193 1.191V9.5l11.069 3.25L30 9.5V4.191A1.19 1.19 0 0 0 28.806 3");
}

</style>
