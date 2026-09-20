<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqcbpabrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqcbpabrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-text-line" /></template>
