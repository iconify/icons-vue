<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdz47bbsa.css';
import '../../css/u/u7f5z2b1k.css';
import '../../css/u/u4oxcdcli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGgkgwBcKe" x1="-432.024" x2="-300.454" y1="625.096" y2="548.928" gradientTransform="rotate(179.846 658.953 976.958)scale(-2.89431 2.89431)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cdz47bbsa"/><stop offset="1" class="u7f5z2b1k"/></linearGradient><path fill="url(#SVGgkgwBcKe)" class="u4oxcdcli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferron" /></template>
