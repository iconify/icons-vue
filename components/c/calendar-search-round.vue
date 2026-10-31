<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocrm3nc-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocrm3nc-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-search-round" /></template>
