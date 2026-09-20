<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi0psjqnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi0psjqnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:coffee-alt" /></template>
