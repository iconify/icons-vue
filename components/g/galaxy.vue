<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e4l6s_b1d.css';
import '../../css/w/wuft_1bog.css';
import '../../css/q/qy6mi32jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e4l6s_b1d"/><path class="wuft_1bog"/><path class="qy6mi32jc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:galaxy" /></template>
