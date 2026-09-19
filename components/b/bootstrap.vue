<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1c8_3xl.css';
import '../../css/y/y-piul0sg.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/y/yv2636mqt.css';
import '../../css/j/jp-des48r.css';
import '../../css/a/att0jkb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGog8GhbrR" x1="76.079" x2="523.48" y1="10.798" y2="365.95" gradientTransform="translate(1.11 14.613)scale(.24566)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vi1c8_3xl"/><stop offset="1" class="y-piul0sg"/></linearGradient><linearGradient id="SVGgmyambZz" x1="193.51" x2="293.51" y1="109.74" y2="278.87" gradientTransform="translate(0 52)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="yv2636mqt"/></linearGradient><filter id="SVGljEujZNk" width="197" height="249" x="161.9" y="135.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="8"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.15 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow"/><feBlend in="SourceGraphic" in2="effect1_dropShadow" result="shape"/></filter></defs><path fill="url(#SVGog8GhbrR)" class="jp-des48r"/><path fill="url(#SVGgmyambZz)" filter="url(#SVGljEujZNk)" transform="translate(1.494 2.203)scale(.24566)" class="att0jkb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bootstrap" /></template>
