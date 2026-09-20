<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kdpl1_b6g.css';
import '../../css/v/vs1hy1byd.css';
import '../../css/n/neg45tb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kdpl1_b6g"/><path clip-rule="evenodd" class="vs1hy1byd"/><path class="neg45tb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:boombox-duotone" /></template>
