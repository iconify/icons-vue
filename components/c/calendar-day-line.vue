<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjtheeblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjtheeblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-day-line" /></template>
