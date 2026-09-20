<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdq7pzc7k.css';
import '../../css/o/ov7ogjxth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdq7pzc7k"/><path class="ov7ogjxth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:conversation-chat" /></template>
