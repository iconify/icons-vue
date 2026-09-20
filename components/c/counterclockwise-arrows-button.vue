<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-1w2b_n.css';
import '../../css/l/lsy2hwxsm.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGIRhXtcEG" class="jf-1w2b_n"/></defs><use href="#SVGIRhXtcEG" class="lsy2hwxsm"/><use href="#SVGIRhXtcEG" class="ij2x_72vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:counterclockwise-arrows-button" /></template>
