<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/w8ssl8bon.css';
import '../../css/d/dtntbjtpx.css';
import '../../css/t/tlhsqgbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w8ssl8bon"/><path class="dtntbjtpx"/><path class="tlhsqgbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-pound" /></template>
