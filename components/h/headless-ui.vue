<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ftyn56r.css';
import '../../css/w/wz1a562zn.css';
import '../../css/s/suqztbcrb.css';
import '../../css/u/uyv_awjwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGno1JGHlx" x1="35.871%" x2="60.314%" y1="7.224%" y2="115.988%"><stop offset="0%" class="l-ftyn56r"/><stop offset="100%" class="wz1a562zn"/></linearGradient><linearGradient id="SVGHMrgPdGo" x1="39.172%" x2="55.05%" y1="0%" y2="99.181%"><stop offset="0%" class="l-ftyn56r"/><stop offset="100%" class="wz1a562zn"/></linearGradient></defs><path fill="url(#SVGno1JGHlx)" class="suqztbcrb"/><path fill="url(#SVGHMrgPdGo)" class="uyv_awjwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:headless-ui" /></template>
