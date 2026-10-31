<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpaf18bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpaf18bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-donut-fill-round" /></template>
