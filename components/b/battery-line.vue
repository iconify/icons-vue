<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbrj6dbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbrj6dbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-line" /></template>
