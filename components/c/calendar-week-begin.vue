<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mrlr1fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5mrlr1fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-week-begin" /></template>
