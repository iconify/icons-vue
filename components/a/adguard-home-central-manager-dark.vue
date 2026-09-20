<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx32gdm7x.css';
import '../../css/a/algf38bxk.css';
import '../../css/g/gdiwj9opj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGURGRZqwM" x1="18.591" x2="534.669" y1="-27.805" y2="488.273" gradientUnits="userSpaceOnUse"><stop offset="0" class="qx32gdm7x"/><stop offset="1"/></linearGradient><path fill="url(#SVGURGRZqwM)" class="algf38bxk"/><path class="gdiwj9opj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguard-home-central-manager-dark" /></template>
