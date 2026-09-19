<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1_bgdc2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t1_bgdc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:double-axis-chart-bar" /></template>
