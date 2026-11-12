<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9c9qvbuf.css';
import '../../css/p/pm5pzwhvz.css';
import '../../css/u/ujmnkboja.css';
import '../../css/s/sejiajbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG0ziOKc7l" x2="512" y1="514" y2="2" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="d9c9qvbuf"/><stop offset="1" class="pm5pzwhvz"/></linearGradient><path fill="url(#SVG0ziOKc7l)" class="ujmnkboja"/><path class="sejiajbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:9router" /></template>
