<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8cy_k2ub.css';
import '../../css/v/vqdeeis2p.css';
import '../../css/q/qwdkftlph.css';
import '../../css/y/ydam-vbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256,"top":-25};
const content = `<path class="n8cy_k2ub"/><path class="vqdeeis2p"/><path class="qwdkftlph"/><path class="ydam-vbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-cloud" /></template>
