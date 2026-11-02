<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yawjzmbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yawjzmbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-check-line" /></template>
