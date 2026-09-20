<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxbvolhhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxbvolhhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoke-ai-dark" /></template>
