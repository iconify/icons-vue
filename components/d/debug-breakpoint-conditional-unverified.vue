<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wjqiubciq.css';
import '../../css/d/d3ei_ywlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="wjqiubciq"/><path class="d3ei_ywlo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-conditional-unverified" /></template>
