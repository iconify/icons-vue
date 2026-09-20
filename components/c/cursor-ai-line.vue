<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw-ivcr5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw-ivcr5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cursor-ai-line" /></template>
