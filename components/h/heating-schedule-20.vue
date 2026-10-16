<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjzgm6b2a.css';
import '../../css/k/ktpspx8sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yjzgm6b2a"/><path class="ktpspx8sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heating-schedule-20" /></template>
