<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_934gbdn.css';
import '../../css/f/f_r188jlf.css';
import '../../css/p/pq9c81bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG6n2XYc7U" x1="19.179" x2="492.821" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="n_934gbdn"/><stop offset="1" class="f_r188jlf"/></linearGradient><path fill="url(#SVG6n2XYc7U)" class="pq9c81bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composr" /></template>
