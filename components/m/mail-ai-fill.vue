<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_x-2hbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_x-2hbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-ai-fill" /></template>
