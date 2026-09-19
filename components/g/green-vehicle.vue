<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l5u4fnbuo.css';
import '../../css/m/m0gfe4xfk.css';
import '../../css/w/wr6g3jo2n.css';
import '../../css/y/yu4vwwb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5u4fnbuo"/><path class="m0gfe4xfk"/><path class="wr6g3jo2n"/><path class="yu4vwwb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:green-vehicle" /></template>
