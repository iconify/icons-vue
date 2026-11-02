<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc3-7_t-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc3-7_t-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hair-line" /></template>
