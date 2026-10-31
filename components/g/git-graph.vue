<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/qn_8dxb9v.css';
import '../../css/q/qjx4q3b5l.css';
import '../../css/b/bv_q14-ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="qn_8dxb9v wm-shadow"/><path class="qjx4q3b5l wm-shadow"/><path class="bv_q14-ra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:git-graph" /></template>
