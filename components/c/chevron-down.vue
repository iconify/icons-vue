<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycd-xybnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ycd-xybnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:chevron-down" /></template>
