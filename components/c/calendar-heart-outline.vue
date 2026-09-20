<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8vo2-1qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8vo2-1qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-heart-outline" /></template>
