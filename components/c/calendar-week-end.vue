<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk-1eiy9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk-1eiy9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-week-end" /></template>
