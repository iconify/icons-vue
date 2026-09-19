<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk5nc2iou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sk5nc2iou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:collaborate" /></template>
