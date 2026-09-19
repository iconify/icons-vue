<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfjgc5bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mfjgc5bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:double-axis-chart-column" /></template>
