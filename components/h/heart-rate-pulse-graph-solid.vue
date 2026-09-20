<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo3aqsb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vo3aqsb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heart-rate-pulse-graph-solid" /></template>
