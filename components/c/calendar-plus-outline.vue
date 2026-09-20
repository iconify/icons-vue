<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su5y6qvyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su5y6qvyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-plus-outline" /></template>
