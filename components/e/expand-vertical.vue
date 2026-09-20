<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf578kboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf578kboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:expand-vertical" /></template>
