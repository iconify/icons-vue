<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw8koyu9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw8koyu9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-arrow-down-fill" /></template>
