<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu7m_8bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu7m_8bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-arrow-left" /></template>
