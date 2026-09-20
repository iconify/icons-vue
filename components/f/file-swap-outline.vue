<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyng10oup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyng10oup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-swap-outline" /></template>
