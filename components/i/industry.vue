<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyoq1mlao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cyoq1mlao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:industry" /></template>
