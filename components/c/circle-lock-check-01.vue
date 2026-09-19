<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yjy9_xhih.css';
import '../../css/d/dtjbxibrj.css';
import '../../css/v/vzi1xbcty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yjy9_xhih"/><path class="dtjbxibrj"/><path class="vzi1xbcty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-lock-check-01" /></template>
