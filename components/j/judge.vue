<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f67gkydna.css';
import '../../css/o/ol3uvlb_q.css';
import '../../css/v/vz8svzz4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="f67gkydna"/><path class="ol3uvlb_q"/><path class="vz8svzz4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:judge" /></template>
