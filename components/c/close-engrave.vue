<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e2hwfubct.css';
import '../../css/l/l-cphhs4g.css';
import '../../css/z/zl-i7yb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e2hwfubct"/><path class="l-cphhs4g wm-shadow"/><path class="zl-i7yb9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:close-engrave" /></template>
