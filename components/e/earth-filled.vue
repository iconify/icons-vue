<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cq5fgnbzq.css';
import '../../css/o/oqtrjux1w.css';
import '../../css/y/y2nul6bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cq5fgnbzq"/><path class="oqtrjux1w"/><path class="y2nul6bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earth-filled" /></template>
