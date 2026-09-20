<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2kzi90wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j2kzi90wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-redirect-rtl" /></template>
