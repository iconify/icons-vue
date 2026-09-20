<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd0ydlb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd0ydlb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:disc-warning" /></template>
