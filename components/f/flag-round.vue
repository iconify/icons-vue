<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu6kx8kiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu6kx8kiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-round" /></template>
