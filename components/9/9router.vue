<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9c9qvbuf.css';
import '../../css/p/pm5pzwhvz.css';
import '../../css/u/ujmnkboja.css';
import '../../css/a/ag3kxs88v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGZYnxua0q" x1="0" x2="512" y1="514" y2="2" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="d9c9qvbuf"/><stop offset="1" class="pm5pzwhvz"/></linearGradient><path fill="url(#SVGZYnxua0q)" class="ujmnkboja"/><path class="ag3kxs88v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:9router" /></template>
