<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8n05qlvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8n05qlvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-search-outline" /></template>
