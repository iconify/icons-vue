<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/o4-575bqq.css';
import '../../css/q/quk2qgbrt.css';
import '../../css/y/ysqxkebtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o4-575bqq"/><path class="quk2qgbrt"/><path class="ysqxkebtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-off-sharp-duotone" /></template>
