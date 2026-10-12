<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_oeqshiy.css';
import '../../css/v/v7-hzldcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_oeqshiy"/><path class="v7-hzldcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-pulse-20-bold" /></template>
