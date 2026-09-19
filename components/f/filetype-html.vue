<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7vklubtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f7vklubtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-html" /></template>
