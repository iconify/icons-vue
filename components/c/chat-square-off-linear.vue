<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o-k-qwbls.css';
import '../../css/r/rjy1xybnj.css';
import '../../css/r/rqx2gjabx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o-k-qwbls"/><path class="rjy1xybnj"/><path class="rqx2gjabx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-off-linear" /></template>
