<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swem9zb9q.css';
import '../../css/m/m2hb1402k.css';
import '../../css/b/bgct7jsbk.css';
import '../../css/f/fetk55mbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<linearGradient id="SVGzsZW5bmW" x1="400.05" x2="400.05" y1="798.772" y2="-1.228" gradientTransform="matrix(1 0 0 -1 0 798.772)" gradientUnits="userSpaceOnUse"><stop offset="0" class="swem9zb9q"/><stop offset="1" class="m2hb1402k"/></linearGradient><path fill="url(#SVGzsZW5bmW)" class="bgct7jsbk"/><path class="fetk55mbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:app-store" /></template>
