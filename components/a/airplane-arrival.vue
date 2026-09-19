<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lguui-g7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lguui-g7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:airplane-arrival" /></template>
