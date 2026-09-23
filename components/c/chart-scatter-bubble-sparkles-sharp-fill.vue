<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w_xe7g5xk.css';
import '../../css/y/yntpkfbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w_xe7g5xk"/><path class="yntpkfbkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-scatter-bubble-sparkles-sharp-fill" /></template>
