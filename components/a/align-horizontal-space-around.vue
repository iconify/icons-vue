<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipxit1bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipxit1bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-space-around" /></template>
