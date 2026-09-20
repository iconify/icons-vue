<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4kanwwph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="t4kanwwph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:day-windy" /></template>
