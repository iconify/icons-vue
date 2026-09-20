<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jx_isobmu.css';
import '../../css/r/rsakbsbbr.css';
import '../../css/l/lr8sivbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jx_isobmu"/><path class="rsakbsbbr"/><path class="lr8sivbky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-bold" /></template>
