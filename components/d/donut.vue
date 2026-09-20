<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/y/yk5i701wb.css';
import '../../css/p/ptkmnzomc.css';
import '../../css/b/brx-gnbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="yk5i701wb"/><path class="ptkmnzomc"/><path class="brx-gnbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:donut" /></template>
