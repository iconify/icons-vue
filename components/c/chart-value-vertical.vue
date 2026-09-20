<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf7fl8b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yf7fl8b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-value-vertical" /></template>
