<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvfd5l4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvfd5l4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-schedule-fill" /></template>
