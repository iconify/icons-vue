<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iegxcwbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iegxcwbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-today-outline" /></template>
