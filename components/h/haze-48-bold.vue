<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d16_u1b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d16_u1b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:haze-48-bold" /></template>
