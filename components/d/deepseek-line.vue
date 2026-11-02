<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzoz7zbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzoz7zbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:deepseek-line" /></template>
