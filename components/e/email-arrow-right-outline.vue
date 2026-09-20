<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc30tubfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc30tubfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-arrow-right-outline" /></template>
