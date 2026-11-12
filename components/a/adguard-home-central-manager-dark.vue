<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx32gdm7x.css';
import '../../css/a/algf38bxk.css';
import '../../css/t/tbxz3xbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGu2Rgje2r" x1="18.6" x2="534.7" y1="-27.8" y2="488.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="qx32gdm7x"/><stop offset="1"/></linearGradient><path fill="url(#SVGu2Rgje2r)" class="algf38bxk"/><path class="tbxz3xbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguard-home-central-manager-dark" /></template>
