<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo_914b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo_914b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-search" /></template>
