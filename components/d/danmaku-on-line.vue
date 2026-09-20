<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9g01ubhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9g01ubhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-on-line" /></template>
