<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc7yyg80f.css';
import '../../css/w/wb84icb0c.css';
import '../../css/y/yiv8uxygr.css';
import '../../css/d/dmx1en81z.css';
import '../../css/s/svqiap0yg.css';
import '../../css/x/x6-l7vufm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVG2BzrrUzr" cx="82.6" cy="75.2" r="99.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="fc7yyg80f"/><stop offset=".85" class="wb84icb0c"/><stop offset="1" class="wb84icb0c"/></radialGradient></defs><path class="yiv8uxygr"/><path fill="url(#SVG2BzrrUzr)" transform="matrix(3 0 0 3 -37.69 -37.69)" class="dmx1en81z"/><path class="svqiap0yg"/><path class="x6-l7vufm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:dim-button" /></template>
