<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8n5syigx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8n5syigx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fries-line" /></template>
