<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-e0uee1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-e0uee1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-vertical-line" /></template>
