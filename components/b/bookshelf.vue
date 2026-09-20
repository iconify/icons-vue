<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx55dmspr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx55dmspr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookshelf" /></template>
