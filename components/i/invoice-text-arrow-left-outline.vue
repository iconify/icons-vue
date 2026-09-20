<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9d33dyrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9d33dyrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-arrow-left-outline" /></template>
