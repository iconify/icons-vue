<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9w93fbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e9w93fbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-aac" /></template>
