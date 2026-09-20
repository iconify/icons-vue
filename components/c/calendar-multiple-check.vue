<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swbrv-bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swbrv-bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-multiple-check" /></template>
