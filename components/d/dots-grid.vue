<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_g7-bncq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_g7-bncq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dots-grid" /></template>
