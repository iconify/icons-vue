<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waxltl5fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waxltl5fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-climate-outline" /></template>
