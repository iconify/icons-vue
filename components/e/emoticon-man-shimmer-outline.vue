<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfwkjt-vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfwkjt-vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-man-shimmer-outline" /></template>
