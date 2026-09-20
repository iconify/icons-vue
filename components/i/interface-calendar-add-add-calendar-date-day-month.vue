<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucwmz4b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ucwmz4b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-calendar-add-add-calendar-date-day-month" /></template>
