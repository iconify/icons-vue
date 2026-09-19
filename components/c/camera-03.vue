<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mum8h13xe.css';
import '../../css/l/lr5p17fsb.css';
import '../../css/s/s3rtijlqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mum8h13xe"/><path class="lr5p17fsb"/><path class="s3rtijlqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-03" /></template>
