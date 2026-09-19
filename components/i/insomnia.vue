<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud98ozx5d.css';
import '../../css/i/i9d11l03r.css';
import '../../css/h/hfwnuldjt.css';
import '../../css/p/pokjuvbmf.css';
import '../../css/a/aj50fybzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVG6ro6benw" x1="16.181" x2="16.181" y1="28.39" y2="5.61" gradientTransform="matrix(4 0 0 4 0 -4)" gradientUnits="userSpaceOnUse"><stop class="ud98ozx5d"/><stop offset="1" class="i9d11l03r"/></linearGradient></defs><path class="hfwnuldjt"/><path class="pokjuvbmf"/><path fill="url(#SVG6ro6benw)" class="aj50fybzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:insomnia" /></template>
