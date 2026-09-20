<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3k4mxcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j3k4mxcjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:left-square-outline" /></template>
