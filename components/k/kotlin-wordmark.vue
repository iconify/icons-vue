<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qea20536a.css';
import '../../css/u/u1ts3dbke.css';
import '../../css/z/z2w67ghwc.css';
import '../../css/i/imshmp5va.css';
import '../../css/n/n88dr0plw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGYo5SDblO" cx="0" cy="0" r="1" fx="0" fy="0" gradientTransform="translate(31.27 41.62)scale(26.70313)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="qea20536a"/><stop offset=".469" class="u1ts3dbke"/><stop offset="1" class="z2w67ghwc"/></radialGradient></defs><path fill="url(#SVGYo5SDblO)" class="imshmp5va"/><path class="n88dr0plw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kotlin-wordmark" /></template>
