<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dqjdzwb4b.css';
import '../../css/g/g-fswfmas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dqjdzwb4b"/><path clip-rule="evenodd" class="g-fswfmas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:diagnostics-outline-24px" /></template>
