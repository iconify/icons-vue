<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq7tt2btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq7tt2btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:attachment-lock" /></template>
