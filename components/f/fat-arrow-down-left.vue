<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtcj90bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtcj90bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-down-left" /></template>
