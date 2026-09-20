<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs-bnnbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs-bnnbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:home-simple" /></template>
