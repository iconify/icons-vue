<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_lksac0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_lksac0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-processor-outline" /></template>
