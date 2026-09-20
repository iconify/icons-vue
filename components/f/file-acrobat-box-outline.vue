<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f97e20-gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f97e20-gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-acrobat-box-outline" /></template>
