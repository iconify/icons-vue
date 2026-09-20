<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjlr4l5vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjlr4l5vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:card" /></template>
