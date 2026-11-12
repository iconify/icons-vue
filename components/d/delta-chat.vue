<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jucv-h4wp.css';
import '../../css/q/qg-yprb1w.css';
import '../../css/q/q4qqzzb3s.css';
import '../../css/r/ro30m2bca.css';
import '../../css/s/svbkngbld.css';
import '../../css/a/akciwwb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jucv-h4wp"/><path class="qg-yprb1w"/><linearGradient id="SVGrgrK1UNG" x1="385.527" x2="-453.267" y1="181.959" y2="708.591" gradientTransform="matrix(.9377 0 0 -.9377 -25.01 475.76)" gradientUnits="userSpaceOnUse"><stop offset="0" class="q4qqzzb3s"/><stop offset="1" class="ro30m2bca"/></linearGradient><path fill="url(#SVGrgrK1UNG)" class="svbkngbld"/><path class="akciwwb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:delta-chat" /></template>
