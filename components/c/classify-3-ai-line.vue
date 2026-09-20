<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwg-msb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwg-msb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-3-ai-line" /></template>
