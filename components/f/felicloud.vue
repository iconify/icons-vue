<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh15ailor.css';
import '../../css/v/v_-jg8uqn.css';
import '../../css/v/vblcbgz4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGImzsOdxr" x1="-689.903" x2="-689.903" y1="788.911" y2="781.8" gradientTransform="matrix(72 0 0 -45 49929 35597)" gradientUnits="userSpaceOnUse"><stop offset="0" class="fh15ailor"/><stop offset="1" class="v_-jg8uqn"/></linearGradient><path fill="url(#SVGImzsOdxr)" class="vblcbgz4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:felicloud" /></template>
