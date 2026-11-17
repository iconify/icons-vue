<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/z/zaffh1bwb.css';
import '../../css/t/t6ehjqagz.css';
import '../../css/j/jutwg48hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="zaffh1bwb"/><path class="t6ehjqagz"/><path class="jutwg48hp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:file-search" /></template>
