<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoshd2brl.css';
import '../../css/e/eww6_fb3u.css';
import '../../css/e/e3vxdac3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGU8b2Jemq" x1="736.964" x2="1738.505" y1="-257.356" y2="-257.356" gradientTransform="matrix(.4945 0 0 -.5112 -356.02 124.436)" gradientUnits="userSpaceOnUse"><stop offset="0" class="eoshd2brl"/><stop offset="1" class="eww6_fb3u"/></linearGradient><path fill="url(#SVGU8b2Jemq)" class="e3vxdac3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budget-board" /></template>
