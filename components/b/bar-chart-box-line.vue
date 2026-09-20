<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml67rq0mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml67rq0mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bar-chart-box-line" /></template>
