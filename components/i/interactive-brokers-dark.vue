<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sll_zg-uo.css';
import '../../css/c/ccqymhpos.css';
import '../../css/l/l6xvejonm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGygEO3diJ" x1="351.3" x2="124.8" y1="387.2" y2="387.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1"/></linearGradient><path fill="url(#SVGygEO3diJ)" class="ccqymhpos"/><path class="l6xvejonm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:interactive-brokers-dark" /></template>
