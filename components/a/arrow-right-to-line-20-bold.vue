<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvilsvvcy.css';
import '../../css/d/d6ukndv1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bvilsvvcy"/><path class="d6ukndv1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-to-line-20-bold" /></template>
