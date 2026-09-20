<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgwalibwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgwalibwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-up" /></template>
