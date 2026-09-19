<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ol9j3tbce.css';
import '../../css/y/y8jq-7b-y.css';
import '../../css/l/lsw_2ibkc.css';
import '../../css/f/f-onb3b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ol9j3tbce"/><path class="y8jq-7b-y"/><path clip-rule="evenodd" class="lsw_2ibkc"/><path class="f-onb3b8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fever-outline-24px" /></template>
