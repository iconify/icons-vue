<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh_9m3lpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh_9m3lpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coathanger-line" /></template>
