<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilj8trt6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilj8trt6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-down-left-line" /></template>
