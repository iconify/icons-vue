<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xz2d1xbtd.css';
import '../../css/o/oy3llbbra.css';
import '../../css/z/zaf1byp1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="xz2d1xbtd"/><path class="oy3llbbra"/><path class="zaf1byp1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:angry-face-with-horns" /></template>
