<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drw4bvb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drw4bvb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-week-begin-outline" /></template>
