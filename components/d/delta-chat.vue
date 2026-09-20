<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jucv-h4wp.css';
import '../../css/k/k7qnr4b6y.css';
import '../../css/q/q4qqzzb3s.css';
import '../../css/r/ro30m2bca.css';
import '../../css/s/svbkngbld.css';
import '../../css/b/b73p0hbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jucv-h4wp"/><path class="k7qnr4b6y"/><linearGradient id="SVGTsfzyccY" x1="385.527" x2="-453.267" y1="181.959" y2="708.591" gradientTransform="matrix(.9377 0 0 -.9377 -25.013 475.762)" gradientUnits="userSpaceOnUse"><stop offset="0" class="q4qqzzb3s"/><stop offset="1" class="ro30m2bca"/></linearGradient><path fill="url(#SVGTsfzyccY)" class="svbkngbld"/><path class="b73p0hbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:delta-chat" /></template>
