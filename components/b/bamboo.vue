<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sav6x4bmf.css';
import '../../css/g/g_gp7lgqe.css';
import '../../css/t/tesxa8efe.css';
import '../../css/r/ri94p7_ze.css';
import '../../css/e/e60zxob-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVG4arXaemu" x1="11.217" x2="11.217" y1="7.486" y2="21.607" gradientTransform="scale(4)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sav6x4bmf"/><stop offset="1" class="g_gp7lgqe"/></linearGradient><linearGradient id="SVGzR0VpdwF" x1="11.168" x2="11.168" y1="7.486" y2="21.607" gradientTransform="scale(4)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sav6x4bmf"/><stop offset="1" class="g_gp7lgqe"/></linearGradient></defs><path class="tesxa8efe"/><path fill="url(#SVG4arXaemu)" class="ri94p7_ze"/><path fill="url(#SVGzR0VpdwF)" class="e60zxob-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bamboo" /></template>
