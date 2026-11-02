<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyysp6bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyysp6bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bilibili-line" /></template>
