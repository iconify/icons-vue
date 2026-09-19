<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnvl1_o4f.css';
import '../../css/j/jt_7erraj.css';
import '../../css/b/bx-y_8bwh.css';
import '../../css/w/w6x7vebin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGIn9ovNMa" x1="4.746" x2="70.607" y1="8.636" y2="59.748" gradientUnits="userSpaceOnUse"><stop class="wnvl1_o4f"/><stop offset="1" class="jt_7erraj"/></linearGradient></defs><path clip-rule="evenodd" class="bx-y_8bwh"/><path fill="url(#SVGIn9ovNMa)" transform="translate(0 48.29)scale(.42782)" class="w6x7vebin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:aiassistant-wordmark" /></template>
