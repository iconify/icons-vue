<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0yat0bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t0yat0bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:filter-48-bold" /></template>
