<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxh8pobme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxh8pobme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-rotation-down-vertical" /></template>
