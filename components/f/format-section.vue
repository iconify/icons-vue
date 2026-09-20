<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-bzc3b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-bzc3b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-section" /></template>
