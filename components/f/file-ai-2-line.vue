<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi8s1omqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi8s1omqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-ai-2-line" /></template>
