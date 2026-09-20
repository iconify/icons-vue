<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmyw_-b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmyw_-b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-ai-fill" /></template>
