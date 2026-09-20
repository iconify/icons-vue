<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc5s19shd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc5s19shd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lightbulb-flash-fill" /></template>
