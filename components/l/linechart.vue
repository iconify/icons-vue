<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg1vbbbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yg1vbbbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:linechart" /></template>
