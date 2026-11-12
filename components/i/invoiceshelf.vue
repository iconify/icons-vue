<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1j9atbnx.css';
import '../../css/x/xxyaynvxj.css';
import '../../css/n/nw8q64y9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGSZQ7UbHW" x1="21.3" x2="490.7" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="d1j9atbnx"/><stop offset="1" class="xxyaynvxj"/></linearGradient><path fill="url(#SVGSZQ7UbHW)" class="nw8q64y9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceshelf" /></template>
