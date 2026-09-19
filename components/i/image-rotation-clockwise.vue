<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/axcbjwqzp.css';
import '../../css/b/bwio8qbtt.css';
import '../../css/z/zlavaxbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="axcbjwqzp"/><path class="bwio8qbtt"/><path class="zlavaxbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-rotation-clockwise" /></template>
