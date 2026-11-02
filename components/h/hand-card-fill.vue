<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rle9alb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rle9alb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-card-fill" /></template>
