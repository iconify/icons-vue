<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="szx0-eb6t"/><path class="ktk9dyhzz"/><path class="mgo7mkb4s"/><path class="ecrw6eiva"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ice-background" /></template>
<style>
.ecrw6eiva {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.985 14.3l-2.875-.195l-.61 1.825L7.275 20h8.235l1.165-5.385l-2.525-3.755l-1.9-.68v.395l-3.265 3.72z");
}

.ft5dv1b6b {
  fill: none;
}

.ktk9dyhzz {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.71 10.66l.55 3.76l4.185.29l2.52-4.76l-1.11-3.87l-1.715-2.04h-.47l-.92.76L7.82 8z");
}

.mgo7mkb4s {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.85 19.11l-1.34.876l-3.21-9.736l-.155-3.11L10.095 4l3.25 2.43l.935 1.785l1.865.735l2.355 5.41z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.szx0-eb6t {
  fill: var(--svg-color--3fdcff, #3fdcff);
  d: path("M24 0H0v24h24z");
}

</style>
