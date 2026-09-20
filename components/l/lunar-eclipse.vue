<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shvum10dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="shvum10dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:lunar-eclipse" /></template>
