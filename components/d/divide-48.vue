<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mse5hd4bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mse5hd4bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:divide-48" /></template>
