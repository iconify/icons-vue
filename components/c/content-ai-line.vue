<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc8tn-bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc8tn-bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:content-ai-line" /></template>
