<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd560hbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd560hbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-fill-round" /></template>
