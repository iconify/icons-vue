<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/epx2zjbrs.css';
import '../../css/t/t2xnnpb2g.css';
import '../../css/q/qifgr8pul.css';
import '../../css/z/zmo714tko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="epx2zjbrs"/><path class="t2xnnpb2g"/><path class="qifgr8pul"/><path class="zmo714tko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:googlecloud-wordmark" /></template>
