<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf2-8lbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2-8lbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:apple-logo-round" /></template>
