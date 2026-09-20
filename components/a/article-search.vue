<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp00_mbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dp00_mbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-search" /></template>
