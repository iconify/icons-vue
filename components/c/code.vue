<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0x_f4h1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0x_f4h1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code" /></template>
