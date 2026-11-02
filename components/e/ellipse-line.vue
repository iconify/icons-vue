<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gctyc2rag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gctyc2rag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ellipse-line" /></template>
