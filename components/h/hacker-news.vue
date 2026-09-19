<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj9jajbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mj9jajbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:hacker-news" /></template>
