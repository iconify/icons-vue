<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":289};
const content = `<defs><path id="SVGACU8jbZk" class="xrzf8lb5a"/></defs><mask id="SVGascSabGB" class="n1mjunbsu"><use href="#SVGACU8jbZk"/></mask><use href="#SVGACU8jbZk" class="la9dvuxjr"/><g mask="url(#SVGascSabGB)"><path class="l2ih_wbvq"/><path class="kurrkoqug"/><path class="uie5tgope"/><path class="lk11cpy6a"/><path class="hm-5nef_s"/><path class="op6h4bcaw"/><path class="vum09hbwg"/><path class="tivh01buj"/><path class="yp7he4bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:buddy" /></template>
<style>
.hm-5nef_s {
  fill: var(--svg-color--1a86fd, #1a86fd);
  d: path("m128 292.859l128-74.143l-189.45-73.905z");
}

.kurrkoqug {
  fill: var(--svg-color--0da7fe, #0da7fe);
  d: path("M66.55 144.811L0 70.431v148.285z");
}

.l2ih_wbvq {
  fill: var(--svg-color--1a67fd, #1a67fd);
  d: path("M66.55 144.811L128 292.859L0 218.716z");
}

.la9dvuxjr {
  fill: var(--svg-color--00c9ff, #00c9ff);
}

.lk11cpy6a {
  fill: var(--svg-color--05bbff, #05bbff);
  d: path("M66.55 144.811L128-3L0 70.431z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.op6h4bcaw {
  fill: var(--svg-color--05bbff, #05bbff);
  d: path("M256 218.716V70.905L128-3z");
}

.tivh01buj {
  fill: var(--svg-color--d6ffff, #d6ffff);
  d: path("M171.299 141.252L155.047 125l-62.042 62.043l16.252 16.252z");
}

.uie5tgope {
  fill: var(--svg-color--00c9ff, #00c9ff);
  d: path("M66.55 144.811L128-3l128 221.716z");
}

.vum09hbwg {
  fill: var(--svg-color--1a67fd, #1a67fd);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m155.047 132.355l16.252 16.252l-8.067 8.067l-8.185 8.185l-45.791 45.791l-16.251-16.253l45.79-45.79l-45.79-45.791l16.251-16.252z");
}

.xrzf8lb5a {
  d: path("M116.612 3.643C92.293 17.641 35.707 50.383 11.389 64.38C4.389 68.414 0 76.006 0 84.073v121.476c0 8.066 4.389 15.659 11.389 19.692c24.2 13.998 80.904 46.739 105.223 60.738c7.117 4.032 15.777 4.032 22.776 0c24.201-13.999 80.905-46.74 105.223-60.738C251.61 221.208 256 213.615 256 205.549V84.073c0-8.185-4.39-15.659-11.389-19.693c-24.2-13.997-80.904-46.739-105.223-60.737A23.2 23.2 0 0 0 127.955.618a22.7 22.7 0 0 0-11.343 3.025");
}

.yp7he4bgy {
  fill: var(--svg-color--d6ffff, #d6ffff);
  d: path("M109.257 79.328L93.123 95.58l62.043 62.043l16.252-16.253c-.12-.118-62.161-62.042-62.161-62.042");
}

</style>
