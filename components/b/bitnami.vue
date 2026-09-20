<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":287};
const content = `<defs><linearGradient id="SVGqHIqdc4h" x1="14.551%" x2="411.685%" y1="49.972%" y2="49.972%"><stop offset="0%" class="stui2mbih"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGorvSldck" x1="5.239%" x2="379.916%" y1="82.91%" y2="-193.342%"><stop offset="0%" class="stui2mbih"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGaKsPLlGG" x1="62.675%" x2="-363.978%" y1="44.012%" y2="243.704%"><stop offset="0%" class="stui2mbih"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGyS5h5cVw" x1="11.134%" x2="355.291%" y1="19.904%" y2="478.171%"><stop offset="0%" class="stui2mbih"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGIUMDkLex" x1="53.115%" x2="46.266%" y1="2.534%" y2="110.506%"><stop offset="0%" class="q20t2s1ps"/><stop offset="100%" class="sfk9ghb6i"/></linearGradient></defs><path class="af0b5qb9w"/><path class="hv1abfb2u"/><path fill="url(#SVGqHIqdc4h)" class="iuoqspbvs"/><path fill="url(#SVGorvSldck)" class="feklocbku"/><path fill="url(#SVGaKsPLlGG)" class="i8-f2-b8r"/><path fill="url(#SVGyS5h5cVw)" class="be96p3b5r"/><path fill="url(#SVGIUMDkLex)" class="gqbwo7bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bitnami" /></template>
<style>
.af0b5qb9w {
  fill: var(--svg-color--2a5d84, #2a5d84);
  d: path("m142.4 3.9l99.3 57.3C251 66.6 256 75.5 256 86.9v114c0 10.8-4.9 19.2-14.1 24.6c-33 19.1-66.1 38.1-99.1 57.2c-9.6 5.6-20 5.5-29.7-.1c-32.9-19-65.9-38-98.8-57.1C6.4 221 0 211.9 0 200.4V81.8c0-10.4 4.9-15.7 14.1-21L53.7 38v148.3l74.3 42.9l74.3-42.9v-85.8L128 57.6l-31.2 18v-62c5.6-3.2 11.2-6.5 16.9-9.7c8.7-5.1 19.5-5.3 28.7 0");
}

.be96p3b5r {
  d: path("M97.9 14.3v59.4L128 56.3l75.4 43.5v.3l48.1-27.6c-2.3-4.2-5.7-7.7-10.4-10.4c-33.1-19-66.2-38.1-99.3-57.2c-8.6-5-19-5-27.6 0c-5.4 3.1-10.9 6.2-16.3 9.4");
}

.feklocbku {
  d: path("m128 178l30.1-17.4v-34.7L128 143.2z");
}

.gqbwo7bvb {
  d: path("M52.6 186.8v-.5c0-50.3.2-98 .2-148.3L14.9 59.8c-8.8 5.1-13.8 11.9-13.8 22v118.6c0 4.9 1.3 9.7 3.6 13.9z");
}

.hv1abfb2u {
  fill: var(--svg-color--1a3b54, #1a3b54);
  d: path("M159.2 125.2v36l-15.6 9l-15.6 9.1l-15.6-9.1l-15.6-9v-36l15.6-9l15.6-9l15.6 9z");
}

.i8-f2-b8r {
  d: path("m128 178l-30.1-17.4v-34.7l30.1 17.3z");
}

.iuoqspbvs {
  d: path("M158.1 125.9L128 108.5l-30.1 17.4l30.1 17.5z");
}

.q20t2s1ps {
  stop-color: var(--svg-color--1a3b54, #1a3b54);
  stop-opacity: 0;
}

.sfk9ghb6i {
  stop-color: var(--svg-color--1a3b54, #1a3b54);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
