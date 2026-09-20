<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e14cibkce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e14cibkce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:calendar-line" /></template>
