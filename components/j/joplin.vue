<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhu-ikbsy.css';
import '../../css/z/zsjzf-bwd.css';
import '../../css/h/hj5shcbbd.css';
import '../../css/i/iq1sfabpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGFQdVUc4w" x1="-552.852" x2="-552.102" y1="-5875.196" y2="-5875.196" gradientTransform="rotate(225 78141.418 -252389.056)scale(82.7393)" gradientUnits="userSpaceOnUse"><stop offset="0" class="yhu-ikbsy"/><stop offset="1" class="zsjzf-bwd"/></linearGradient><path fill="url(#SVGFQdVUc4w)" class="hj5shcbbd"/><path class="iq1sfabpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:joplin" /></template>
