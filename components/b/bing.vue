<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pv5xoy4cx.css';
import '../../css/g/gi7t4nbmx.css';
import '../../css/c/cm4rcmp0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pv5xoy4cx"/><path class="gi7t4nbmx"/><path class="cm4rcmp0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bing" /></template>
