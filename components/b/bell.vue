<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8xx3g2mm.css';
import '../../css/x/xdgtrbc8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="p8xx3g2mm"/><path class="xdgtrbc8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:bell" /></template>
