<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh46zz4eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh46zz4eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-star-fill" /></template>
