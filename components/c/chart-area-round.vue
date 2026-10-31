<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygi4r2b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygi4r2b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-round" /></template>
