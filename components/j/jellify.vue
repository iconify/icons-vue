<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfwnkk0kz.css';
import '../../css/u/u4rnc5uqo.css';
import '../../css/r/rpsfcsbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGmH67Ny9b" x1="-423.973" x2="-301.184" y1="670.216" y2="547.427" gradientTransform="matrix(2.8346 0 0 -2.8346 1290.117 1975.458)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qfwnkk0kz"/><stop offset="1" class="u4rnc5uqo"/></linearGradient><path fill="url(#SVGmH67Ny9b)" class="rpsfcsbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jellify" /></template>
