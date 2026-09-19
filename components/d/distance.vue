<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cespfdc7o.css';
import '../../css/y/ywyedej2p.css';
import '../../css/h/hztvveiae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="cespfdc7o"/><path class="ywyedej2p"/><path class="hztvveiae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:distance" /></template>
