<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/a/algf38bxk.css';
import '../../css/d/d3blh1bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG2oBCYb7q" x1="18.591" x2="534.669" y1="-27.805" y2="488.273" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG2oBCYb7q)" class="algf38bxk"/><path class="d3blh1bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguard-home-central-manager-light" /></template>
