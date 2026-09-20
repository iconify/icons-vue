<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgbsngblv.css';
import '../../css/x/xdl23sb0e.css';
import '../../css/z/zjhvbexqd.css';
import '../../css/p/pgeacdcrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGD0PzcbSw" x1="97.487" x2="522.047" y1="483.902" y2="729.018" gradientTransform="translate(0 -278)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zgbsngblv"/><stop offset="1" class="xdl23sb0e"/></linearGradient><path fill="url(#SVGD0PzcbSw)" class="zjhvbexqd"/><linearGradient id="SVGT2kwWOMz" x1="94.186" x2="518.747" y1="489.619" y2="734.735" gradientTransform="translate(0 -278)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zgbsngblv"/><stop offset="1" class="xdl23sb0e"/></linearGradient><path fill="url(#SVGT2kwWOMz)" class="pgeacdcrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jellyfin" /></template>
