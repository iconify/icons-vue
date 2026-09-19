<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/nv71sffwz.css';
import '../../css/y/yofq8jbuu.css';
import '../../css/c/cd5h0xb6g.css';
import '../../css/k/k_kb5mclh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="nv71sffwz"/><path class="yofq8jbuu"/><path class="cd5h0xb6g"/><path class="k_kb5mclh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:gm" /></template>
