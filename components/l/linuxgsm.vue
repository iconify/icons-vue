<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl0-c8l3p.css';
import '../../css/q/qys2e9brc.css';
import '../../css/e/e28e5w85u.css';
import '../../css/i/i_5l7sllo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl0-c8l3p"/><path class="qys2e9brc"/><linearGradient id="SVGAFgQ5hHm" x1="69.369" x2="69.369" y1="321.536" y2="486.856" gradientTransform="translate(47.893 -956.165)scale(3.0013)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="e28e5w85u"/></linearGradient><path fill="url(#SVGAFgQ5hHm)" class="i_5l7sllo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linuxgsm" /></template>
