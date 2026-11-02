<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybirwlbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybirwlbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-ai-fill" /></template>
