<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvycvgblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvycvgblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-timer" /></template>
