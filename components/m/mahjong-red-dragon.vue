<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r33qufjhi.css';
import '../../css/o/o3kh53buu.css';
import '../../css/h/hfhg49b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r33qufjhi"/><path class="o3kh53buu"/><path class="hfhg49b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mahjong-red-dragon" /></template>
