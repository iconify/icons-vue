<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo315ybiu.css';
import '../../css/y/yhc5jdzvp.css';
import '../../css/u/u27udoylh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGQo9EYaXm" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="xo315ybiu"/><stop offset="1" class="yhc5jdzvp"/></linearGradient><path fill="url(#SVGQo9EYaXm)" class="u27udoylh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:folderhost" /></template>
