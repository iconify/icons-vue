<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cns8dzbnj.css';
import '../../css/z/zshdeb55g.css';
import '../../css/d/dau5s7bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cns8dzbnj"/><path class="zshdeb55g"/><path class="dau5s7bgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:corkscrew-duotone" /></template>
