<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/drr99_06v.css';
import '../../css/w/whufb0eev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="chart-column-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="drr99_06v"/><path class="whufb0eev"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:chart-column-outline" /></template>
