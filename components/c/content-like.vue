<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf7z-yejv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yf7z-yejv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-like" /></template>
