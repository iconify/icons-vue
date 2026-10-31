<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybi9iwwhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybi9iwwhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gitlab-fill-round" /></template>
