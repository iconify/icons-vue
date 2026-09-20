<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oae5odbze.css';
import '../../css/s/stcmdibrh.css';
import '../../css/d/d086ypt1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oae5odbze"/><path class="stcmdibrh"/><path class="d086ypt1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filters-bold" /></template>
