<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wfo5e4vzc.css';
import '../../css/t/tnmupxbzr.css';
import '../../css/t/td21-u-yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wfo5e4vzc"/><path class="tnmupxbzr"/><path class="td21-u-yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-sketch" /></template>
