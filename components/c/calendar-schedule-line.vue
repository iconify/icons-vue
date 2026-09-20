<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e51pr79qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e51pr79qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-schedule-line" /></template>
