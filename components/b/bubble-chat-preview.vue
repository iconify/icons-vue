<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddvgu8bvv.css';
import '../../css/a/ao6h7dxtx.css';
import '../../css/l/lcki00bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="ao6h7dxtx"/><path class="lcki00bvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-preview" /></template>
