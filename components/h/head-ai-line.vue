<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tokhx3bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tokhx3bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:head-ai-line" /></template>
