<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umm606kxf.css';
import '../../css/a/ab6liccyo.css';
import '../../css/d/d-79jbeyd.css';
import '../../css/p/pj24n-bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="umm606kxf"><path class="ab6liccyo"/><path class="d-79jbeyd"/><path class="pj24n-bxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-stickies-color:graph-bar" /></template>
