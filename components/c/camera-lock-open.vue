<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpwu6f97s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpwu6f97s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-lock-open" /></template>
