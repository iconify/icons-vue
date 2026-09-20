<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGvuNYTdXb" x1="111.945%" x2="11.893%" y1="50.038%" y2="50.038%"><stop offset="0%" class="z65hc5b4d"/><stop offset="91.7%" class="bzg--8baj"/></linearGradient><linearGradient id="SVG24zwfdOT" x1="49.967%" x2="49.967%" y1="9.168%" y2="157.332%"><stop offset="0%" class="z65hc5b4d"/><stop offset="100%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVGx56S3bWx" x1="148.041%" x2="-.965%" y1="124.788%" y2="14.925%"><stop offset="10.5%" class="z65hc5b4d"/><stop offset="96.7%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVG2szVDdmM" x1="84.527%" x2="39.512%" y1="-7.697%" y2="70.416%"><stop offset="23.5%" class="z65hc5b4d"/><stop offset="74%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVGkYXzoebA" x1="49.867%" x2="49.867%" y1="-24.305%" y2="65.375%"><stop offset="8.4%" class="q46w5xbaf"/><stop offset="53.8%"/></linearGradient></defs><path fill="url(#SVGvuNYTdXb)" class="qvd7cqbjz"/><path class="m5-zz5rdx"/><path fill="url(#SVG24zwfdOT)" class="jkkwnw53m"/><path fill="url(#SVGx56S3bWx)" class="w5t9sxxbw"/><path fill="url(#SVG2szVDdmM)" class="o-y1gjb7q"/><path fill="url(#SVGkYXzoebA)" class="w3rgyjbcw"/><path class="xg-bt4bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dataspell" /></template>
<style>
.bzg--8baj {
  stop-color: var(--svg-color--fcf84a, #fcf84a);
}

.jkkwnw53m {
  d: path("M137.333 84.8L256 60.8v112.267l-81.6 30.667l-33.334-30.401z");
}

.m5-zz5rdx {
  fill: var(--svg-color--21d789, #21d789);
  d: path("m256 60.8l-112 48.533L164.533 0z");
}

.o-y1gjb7q {
  d: path("m52.8 0l116.8 64.533L129.333 256h-68L2.4 195.2z");
}

.q46w5xbaf {
  stop-color: var(--svg-color--878585, #878585);
}

.qvd7cqbjz {
  d: path("m164.533 0l5.067 104L40 155.2L0 51.733z");
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.w3rgyjbcw {
  d: path("M206 50H50v156h156z");
}

.w5t9sxxbw {
  d: path("m88 52l81.874 12.667L256 172.069L173.33 204l-31.9-31.667z");
}

.xg-bt4bcy {
  fill: var(--svg-color--fff, #fff);
  d: path("M125.4 179.133H67.333v9.534H125.4zM68 70h22.808c18.504 0 30.986 12.48 30.986 28.832c0 16.354-12.48 29.264-30.986 29.264L68 128.528zm12.91 12.05v34.857h9.898c10.328 0 17.645-6.885 17.645-17.213c0-10.33-6.887-17.644-17.645-17.644zM128 119.68l7.54-9.1c5.2 4.42 10.92 7.02 17.42 7.02c5.2 0 8.58-2.08 8.58-5.46v-.26c0-3.38-2.08-4.94-11.7-7.54c-11.96-2.86-19.5-6.24-19.5-17.94v-.26c0-10.66 8.58-17.68 20.54-17.68c8.58 0 15.86 2.6 21.84 7.54l-6.76 9.62c-5.2-3.64-10.4-5.72-15.34-5.72s-7.54 2.34-7.54 5.2v.26c0 3.9 2.6 5.2 12.74 7.8c11.96 3.12 18.72 7.28 18.72 17.68v.26c0 11.7-8.84 18.2-21.58 18.2c-8.84-.26-17.94-3.38-24.96-9.62");
}

.z65hc5b4d {
  stop-color: var(--svg-color--21d789, #21d789);
}

</style>
