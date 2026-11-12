<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcjni6bfe.css';
import '../../css/l/l1q0m9wzl.css';
import '../../css/f/f8mck9vds.css';
import '../../css/n/nh_zuobhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG9QwVbdSQ" x1="256" x2="256" y1="510" y2="11" gradientUnits="userSpaceOnUse"><stop offset="0" class="rcjni6bfe"/><stop offset="1" class="l1q0m9wzl"/></linearGradient><path fill="url(#SVG9QwVbdSQ)" class="f8mck9vds"/><path class="nh_zuobhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-music" /></template>
