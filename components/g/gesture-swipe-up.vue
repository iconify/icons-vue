<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x71lr6bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x71lr6bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-swipe-up" /></template>
