<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig_zqygux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ig_zqygux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:day-snow-thunderstorm" /></template>
