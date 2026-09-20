<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i84m_g4-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i84m_g4-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:encryption-add-outline" /></template>
