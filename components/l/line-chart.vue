<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq08zehts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1536};
const content = `<path class="xq08zehts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:line-chart" /></template>
