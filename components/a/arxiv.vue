<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3__alb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="m3__alb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:arxiv" /></template>
