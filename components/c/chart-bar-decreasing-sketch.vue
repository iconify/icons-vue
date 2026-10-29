<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ekfw6raai.css';
import '../../css/z/zuar5lbsy.css';
import '../../css/b/bhhd6db8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ekfw6raai wm-a"/><path class="wm-k zuar5lbsy"/><path class="bhhd6db8f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-decreasing-sketch" /></template>
