<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoshd2brl.css';
import '../../css/e/eww6_fb3u.css';
import '../../css/a/axg085ttp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGZ7CueRSe" x1="736.964" x2="1738.505" y1="-257.356" y2="-257.356" gradientTransform="matrix(.4945 0 0 -.5112 -356.02 124.44)" gradientUnits="userSpaceOnUse"><stop offset="0" class="eoshd2brl"/><stop offset="1" class="eww6_fb3u"/></linearGradient><path fill="url(#SVGZ7CueRSe)" class="axg085ttp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budget-board" /></template>
