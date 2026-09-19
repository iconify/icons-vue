<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/li8omp20o.css';
import '../../css/t/typubzb2u.css';
import '../../css/q/qxxbbs_qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="li8omp20o"/><path clip-rule="evenodd" class="typubzb2u"/><path clip-rule="evenodd" class="qxxbbs_qk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:elevator" /></template>
