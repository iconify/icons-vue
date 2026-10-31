<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/h/hhv12y3up.css';
import '../../css/q/qok006pqr.css';
import '../../css/v/vqeyk70cs.css';
import '../../css/b/bmpq50y2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="hhv12y3up wm-shadow"/><path class="qok006pqr wm-shadow"/><path class="vqeyk70cs"/><path class="bmpq50y2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:bell" /></template>
