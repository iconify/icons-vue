<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc5-o5lsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zc5-o5lsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:growth-chart-fill-16" /></template>
