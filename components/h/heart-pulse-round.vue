<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpi0bvd3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpi0bvd3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-pulse-round" /></template>
