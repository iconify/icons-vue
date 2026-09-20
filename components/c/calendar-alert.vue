<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nswil6bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nswil6bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-alert" /></template>
