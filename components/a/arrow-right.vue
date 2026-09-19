<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgdlmx9qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgdlmx9qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-right" /></template>
