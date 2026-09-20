<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxhhabct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxhhabct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:compass-line" /></template>
