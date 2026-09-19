<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yolz4bbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yolz4bbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:d" /></template>
