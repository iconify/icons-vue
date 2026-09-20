<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGt2JeocQW" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="19%" class="xtrtznbzt"/><stop offset="90%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVGN4BeKRmQ" x1="65.642%" x2="16.245%" y1="103.177%" y2="34.031%"><stop offset="9%" class="z65hc5b4d"/><stop offset="48%" class="xtrtznbzt"/><stop offset="90%" class="r_lf9ybqi"/></linearGradient></defs><path class="mvkc8jb_q"/><path fill="url(#SVGt2JeocQW)" class="ckxn_yj1v"/><path fill="url(#SVGt2JeocQW)" class="z9wmn6b7l"/><path fill="url(#SVGN4BeKRmQ)" class="nwg3oob6a"/><path class="wj8kk3bmp"/><path class="x7_cdpdli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:appcode" /></template>
<style>
.ckxn_yj1v {
  d: path("M255.253 205.333L195.627 256l-85.094-21.92z");
}

.mvkc8jb_q {
  fill: var(--svg-color--087cfa, #087cfa);
  d: path("M195.627 256L256 96.373l-48-10.88z");
}

.nwg3oob6a {
  d: path("m223.36 148.213l-38.107-65.04l.72-.453L140.48 0L0 151.707V256l255.253-50.667z");
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.wj8kk3bmp {
  d: path("M48 48h160v160H48z");
}

.x7_cdpdli {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.947 177.76h60v10h-60zm112.24-101.573l-8.48 9.786a22.3 22.3 0 0 0-15.467-6.826c-10.073 0-17.383 8.266-17.544 18.481l-.003.532c0 10.373 7.174 19.013 17.547 19.013c6.436 0 10.556-2.315 15.015-6.212l.655-.582l.33-.299l8.373 8.587a31.01 31.01 0 0 1-24.8 10.666a30.533 30.533 0 0 1-31.044-30.517l.004-.656a30.747 30.747 0 0 1 31.547-31.28a31.28 31.28 0 0 1 23.867 9.307M101.333 68l25.547 60.08h-13.707l-5.333-13.333H82.507l-5.334 13.333H63.84L89.333 68zm-6.186 15.76l-8 19.36h16z");
}

.xtrtznbzt {
  stop-color: var(--svg-color--07c3f2, #07c3f2);
}

.z65hc5b4d {
  stop-color: var(--svg-color--21d789, #21d789);
}

.z9wmn6b7l {
  d: path("m31.867 117.28l-27.2-77.813L140.48 0z");
}

</style>
