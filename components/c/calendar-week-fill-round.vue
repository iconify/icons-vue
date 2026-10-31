<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvzc5l46x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvzc5l46x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-week-fill-round" /></template>
