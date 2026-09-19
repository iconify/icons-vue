<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s31ytta8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s31ytta8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-donut" /></template>
