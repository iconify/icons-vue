<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmdl76rvq.css';
import '../../css/q/qfigp90_r.css';
import '../../css/w/wddurxbfu.css';
import '../../css/c/ccc8hxjsk.css';
import '../../css/g/g3q5w3qns.css';
import '../../css/c/c-vp4szgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":231};
const content = `<defs><radialGradient id="SVGL4PcjdRT" cx="53.096%" cy="49.564%" r="93.348%" fx="53.096%" fy="49.564%" gradientTransform="matrix(.77604 0 0 1 .119 0)"><stop offset="0%" class="zmdl76rvq"/><stop offset="45%" class="qfigp90_r"/><stop offset="100%" class="wddurxbfu"/></radialGradient></defs><path fill="url(#SVGL4PcjdRT)" class="ccc8hxjsk"/><path class="g3q5w3qns"/><path class="c-vp4szgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fly" /></template>
